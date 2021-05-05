# Fluxo de Eventos: Cliente

## Fluxo de Eventos: Criar conta

### Fluxo principal

* Sistema solicita os dados pessoais do usuário;
* Cliente digita seus dados pessoais;
* Cliente recebe uma confirmação em seu email cadastrado junto com sua senha de acesso;
* Cliente consegue acessar sua conta no sistema.

### Fluxo alternativo

* Cliente digita seus dados pessoais inválidos (email invalido);
* Cliente não consegue fazer a verificação em seu email e não tem acesso a sua senha;
* Cliente não consegue acessar sua conta.


## Fluxo de Eventos: Fazer login

### Fluxo principal

* Sistema solicita os dados do login e senha;
* Cliente digita seus dados;
* Cliente confirmar as entradas e clique em logar;
* Sistemas verificam seu login e senha;
* Se o login e senha forem válidos o login é feito com sucesso.

### Fluxo alternativo

* Cliente fornece login ou senha inválida;
* Cliente recebe um erro "login ou senha inválidas";
* Cliente clicar em esqueci e é enviado uma nova senha para seu email;
* Caso o cliente não tenha conta, ele pode criar sua nova conta.


## Fluxo de Eventos: Fazer compra

### Fluxo principal

* Cliente escolhe o produto ou serviço da loja;
* Cliente é redirecionado para o carrinho de compras;
* Cliente tem a opção de voltar para a loja e continuar a comprar, ou finalizar compra;
* Cliente solicita finalizar compra;
* Cliente faz o login no sistema;
* Cliente escolhe meio de pagamento;
* Cliente realiza pagamento;
* Compra finalizada com sucesso.

### Fluxo alternativo

* Cliente escolhe a opção de continuar fazendo compras;
* Cliente escolhe outro produto ou serviço da loja;
* Cliente solicita finalizar compra;
* Cliente tem a opção de fazer a compra sem fazer cadastro;
* Cliente preenche os dados para a entrega e dados para contato;
* Cliente seleciona a opção de fazer o pagamento quando receber a entrega;
* A mercadoria chega na casa do cliente;
* Compra finalizada com sucesso.


## Fluxo de Eventos: Avaliação

### Fluxo principal

* Cliente faz login em sua conta;
* Cliente seleciona produto/serviços para ser avaliados.
* Cliente faz avaliação de determinado produto ou serviço com sucesso.

### Fluxo alternativo

* Cliente tenta avaliar o produto/serviço;
* Cliente não fez a compra desse produto/serviço;
* O sistema retorna um erro: "Você não pode avaliar um item que não comprou";
* Cliente é redirecionado a home.

### Fluxo alternativo

* Cliente tenta fazer avaliação sem loga na sua conta.
* Cliente recebe um erro.
* Cliente é redirecionado a pagina de login.

 
## Fluxo de Eventos: Adotar pet

### Fluxo principal

* Cliente clica na page de adoções
* Cliente é redirecionado para pagina de adoção.
* Cliente entra em contado com instituição.

# Fluxo de Eventos: Administrador

## Fluxo de Eventos: Fazer cadastro de produto, serviços e adoções.

### Fluxo principal

* Sistema pede o user e senha do administrador.
* Administrador inserir seu login e senha.
* Administrador faz autenticação na pagina da administração.
* Administrador vai para page de cadastro de produto ou serviço ou adoções.
* Sistema solicita dados do produto, serviço ou adoções.
* Administrador inseri os dados do produto, serviço ou adoções.
* Administrador verificar os dados do produto, serviço ou adoções..
* Administardor finaliza cadastro.

### Fluxo alternativo

* Sistema pede o user e senha do administrador.
* Administrador inserir seu login ou senha senha invalida.
* Sistema emiti uma messagem de erro.
* Administrador não consegue fazer cadastro.

## Fluxo de Eventos: Fazer listagem, edição e exclusão de produto, serviços e adoções.

### Fluxo principal

* Sistema pede o user e senha do administrador.
* Administrador inserir seu login e senha.
* Administrador faz autenticação na pagina da administração.
* Administrador vai para page de listar de produto ou serviço ou adoções.
* Administrador tem a opçao de ver detalhes editar ou excluir produtos, serviços ou adoções.
* Administardor finaliza a listagem, edição ou exclusão.

### Fluxo alternativo

* Sistema pede o user e senha do administrador.
* Administrador inserir seu login ou senha senha invalida.
* Sistema emiti uma messagem de erro.
* Administrador não consegue fazer listagem, edição e exclusão dos produtos ou serviços ou adoções.


