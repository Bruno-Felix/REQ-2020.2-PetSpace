
# Caso de Uso: **Avaliar um Produto**

## 1. Breve Descrição
Esse caso de uso descreve os possiveis fluxos de atividades em "Avaliar um Produto". Esse fluxo de eventos como principal objetivo a avaliação de um produto que o usuário tenha comprado.

## 2. Atores
* Cliente
    
## 3. Condições Prévias
* Ter comprado ao menos um produto.

## 4. Fluxo Básico de Eventos (FBE)

* 4.1 Este caso de uso é iniciado quando o Cliente deseja avaliar um produto;
* 4.2 Cliente seleciona um produto ofertado dentro da plataforma;
* 4.3 Cliente clica em avaliações daquele produto selecionado; 
* 4.4 Cliente escolhe uma classificação de 0 a 5 e faz um comentário opcional;(FEE-01)(RN-01)
* 4.5 Cliente faz um comentário sobre o produto;(FEE-02)
* 4.6 Cliente insere seu nome e seu email;(FEE-02)
* 4.7 Cliente seleciona (não) a opção de "Salvar meus dados neste navegador para a próxima vez que eu comentar";
* 4.8 Cliente clica em enviar a avaliação; (RN-02)
* 4.9 Sistema mostra a avaliação feita com o status de "Esperando Aprovação";
* 4.10 O caso de uso é encerrado.


## 5. Fluxos Alternativos de Eventos (FAE)


## 6. Fluxo de Execção de Eventos (FEE)
* 6.1 **FEE-01: Classificação da Avaliação não escolhida:** No passo 4.4 (FBE) caso o Cliente não escolha uma classificação para avaliação, o sistema mostra-rá uma a memsagem: "Selecione uma classificação". E, o caso de uso retorna ao passo 4.5 do FB;

* 6.2 **FEE-02: Campos não preechidos:** Nos passos 4.5 e 4.6 (FBE) caso o Clente não informar os campos predidos, o sistema mostra uma a memsagem: "Preencha o campo". E, o caso de uso retorna ao passo 4.7 do FB.

## 7- Regra de Négócio (RN)
* 7.1 **RN-01:** Ao escolher uma classificação para a avaliação no passo 4.4 (FBE), só é permitido a escolha de 0 a 5 estrelas;
* 7.2 **RN-02:** Ao enviar uma avaliação no passo 4.8 (FBE), a avaliação vai para o administrador para ser aprovada.
* 7.3 **RN-03:** Ao escolhar a opção de "Salvar meus dados neste navegador para a próxima vez que eu comentar" no passo 4.7, seu nome e email ficarão salvos futuras avaliações.

## 8. Pós-condições

* **FBE:** Cadastro de novos produto;
* **FAE:** Cancelar cadastro de produto.


## 9. Pontos de Extensão

* Não se aplica









