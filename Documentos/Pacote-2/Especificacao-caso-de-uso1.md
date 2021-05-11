
# Caso de Uso: **Fazer cadastro de produto**

## 1- Breve Descrição
Esse caso de uso descreve os possiveis fluxos de atividades que são navegaveis do "Fazer cadasto de produto". Esse fluxo de eventos tem o principal objetivo de cadastra um produto na loja virtual Pet space.

## 2- Atores
 * Administrador
    
## 3- Condições Prévias

* Não se aplica

## 4- Fluxo Básico de Eventos (FBE)

* 4.1- Sistema pede o user e senha do administrador. (FEE-01)(FEE-02)
* 4.2- Administrador inserir seu login, senha e confere os respectivos dados e dar um "ENTER".
* 4.3- Administrador faz autenticação na página do administrador.
* 4.4- Administrador vai para page de cadastro de produto.
* 4.5- Sistema verifica se o produto já existe.
* 4.6- Sistema solicita dados do produto.
* 4.7- Administrador inseri os dados do produto e logo após verifica os dandos antes de confirma.
* 4.8- Adminitrador confirma o cadastro.(FAE-01)
* 4.9- O caso de uso é finalizado.


## 5- Fluxos Alternativos de Eventos (FAE)

* 5.1- **FAE-01: Cancelar cadastro de produto:**
    * 5.1.1- O fluxo alternativo é acionado quando o administrador quer cancelar o cadastro depois que chega no passo 4.7 do FBE
    * Administrador cancelar a opção de confirmar.
    * Caso de uso segue para o passo 4.4

## 6- Fluxo de Execção de Eventos (FEE)
* 6.1- **FEE-01: User inválida:** No passo 4.2 (FBE) caso o user for invalida o sitema retorna a messagem: "Nome de usuário desconhecido. Verifique novamente ou tente seu endereço de e-mail." 
* 6.2- **FEE-02: Senha inválida:** No passo 4.2 (FBE) casoa a senha seja invalida o sistema vai retorna a messagem: "Erro: A senha informada para o usuário user está incorreta. Perdeu a senha?"

## 7- Regra de Négócio (RN)
* Não se aplica

## 8- Pós-condições

* **FBE:** Cadastro de novos produto.
* **FAE:** Cancelar cadastro de produto


## 9- Pontos de Extensão

* Não se aplica








