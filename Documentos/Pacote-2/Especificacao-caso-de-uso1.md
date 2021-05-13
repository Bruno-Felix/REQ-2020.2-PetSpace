# Caso de Uso: **Avaliar um Produto**

## 1. Breve Descrição
Esse caso de uso descreve os possiveis fluxos de atividades em "Avaliar um Produto". Esse fluxo de eventos como principal objetivo a avaliação de um produto que o usuário tenha comprado.

## 2. Atores
* Cliente.
    
## 3. Condições Prévias
* Não se aplica.

## 4. Fluxo Básico de Eventos (FBE)

* 4.1 Este caso de uso é iniciado quando o Cliente deseja avaliar um produto;
* 4.2 Cliente seleciona um produto ofertado dentro da plataforma;
* 4.3 Cliente clica em avaliações daquele produto selecionado;(FAE-01)
* 4.4 Cliente escolhe uma classificação de 1 a 5;(FEE-01)(RN-01)
* 4.5 Cliente faz uma avaliação sobre o produto sobre o produto;(FEE-02)
* 4.6 Cliente clica em enviar a avaliação;(RN-02)
* 4.7 Sistema mostra a avaliação feita com o status de "A sua avaliação está aguardando aprovação";(RN-02)
* 4.8 O caso de uso é encerrado.

## 5. Fluxos Alternativos de Eventos (FAE)
* 5.1 **FAE-01: Cliente não logado:** No passo 4.3 (FBE) quando o Cliente clica em avaliações daquele produto selecionado mas não está logado no site.
    * 5.1.1 Cliente insere seu nome e seu email;(FEE-02)(FEE-03)(FEE-04)(FEE-05)(RN-04)
    * 5.1.2 Cliente seleciona, ou não, a caixa de seleção de "Salvar meus dados neste navegador para a próxima vez que eu comentar";(RN-03)
    * 5.1.3 O caso de uso retorna ao passo 4.4 do FBE.

## 6. Fluxo de Execção de Eventos (FEE)
* 6.1 **FEE-01: Classificação da Avaliação não escolhida:** No passo 4.4 (FBE) caso o Cliente não escolha uma classificação para avaliação, o sistema mostra-rá uma a memsagem: "Selecione uma classificação". E, o caso de uso retorna ao passo 4.4 do FBE;

* 6.2 **FEE-02: Campos não preechidos:** Nos passos 4.5 ou 5.1.1 (FAE) caso o Cliente não informar os campos necessários, o sistema mostra uma a memsagem: "Preencha o campo". E, o caso de uso retorna ao passo 4.5 ou 5.1.1 do FBE;

* 6.3 **FEE-03: Email Inválido:** No passo 5.1.1 (FAE) caso o Cliente não insira um email válido, o sistema o redireciona para uma página com a mensagem "Erro: Digite um endereço de e-mail válido.". E, o caso de uso retorna ao passo 4.2 do FBE;

* 6.4 **FEE-04: Email sem "@":** No passo 5.1.1 (FAE) caso o Cliente insira um email sem o caracter "@", o sistema mostra uma mensagem: "Inclua um "@" no endereço de e-mail". E, o caso de uso retorna ao passo 5.1.1 do FBE;

* 6.5 **FEE-05: "." em posição incorreta** No passo 5.1.1 (FAE) caso o Cliente insira um email com o caracter "." numa posição incorreta, o sistema mostra uma mensagem: ""." está sendo usado em uma posição incorreta". E, o caso de uso retorna ao passo 5.1.1 do FBE.

## 7. Regra de Négócio (RN)
* 7.1 **RN-01:** Ao escolher uma classificação para a avaliação no passo 4.4 (FBE), só é permitido a escolha de 1 a 5 estrelas;
* 7.2 **RN-02:** Ao enviar uma avaliação no passo 4.6 (FBE), a avaliação vai para o administrador para ser aprovada;
* 7.3 **RN-03:** Ao escolhar a opção de "Salvar meus dados neste navegador para a próxima vez que eu comentar" no passo 5.1.2, seu nome e email ficarão salvos futuras avaliações;
* 7.4 **RN-04:** No passo 5.1.1 (FAE), para ser considerado válido o e-mail deve conter: ‘@’ e ‘.com’ e/ou ‘.br’.

## 8. Pós-condições

* **FBE:** Avaliação é criada e enviada aprovação do administrador;

## 9. Pontos de Extensão

* Não se aplica