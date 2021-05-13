
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
* 4.4- Administrador vai para page de cadastro de produto, que se localiza no lado direito do menu onde tem na sidebar com o topico de nome produto.
clica no produdo.
* 4.6- Sistema solicita dados do produto.
* 4.7- Administrador inseri os dados do produto e logo após verifica os dandos antes de confirma. (RN-01) 
* 4.8- Adminitrador confirma o cadastro cliclando em Publicar.(FAE-01)
* 4.9- O caso de uso é finalizado.


## 5- Fluxos Alternativos de Eventos (FAE)

* 5.1- **FAE-01: Cancelar cadastro de produto:**
    * 5.1.1- O fluxo alternativo é acionado quando o administrador quer cancelar o cadastro depois que chega no passo 4.7 do FBE
    * O Administrador cliclar na opção "Mover para lixeira" para cancelar o cadastro do produto.
    * Caso de uso segue para o passo 4.4

## 6- Fluxo de Execção de Eventos (FEE)
* 6.1- **FEE-01: User inválida:** No passo 4.2 (FBE) caso o user for invalida o sitema retorna a messagem: "Nome de usuário desconhecido. Verifique novamente ou tente seu endereço de e-mail." 
* 6.2- **FEE-02: Senha inválida:** No passo 4.2 (FBE) casoa a senha seja invalida o sistema vai retorna a messagem: "Erro: A senha informada para o usuário user está incorreta. Perdeu a senha?"

## 7- Regra de Négócio (RN)
* 7.1- **RN-01:** Ao colocar as informções do produto do passo 4.6 (FBE) onde na categoria de preços, só é permitido a entrada como ponto decimal.

## 8- Pós-condições

* **FBE:** Cadastro de novos produto.
* **FAE:** Cancelar cadastro de produto


## 9- Pontos de Extensão

* Não se aplica








