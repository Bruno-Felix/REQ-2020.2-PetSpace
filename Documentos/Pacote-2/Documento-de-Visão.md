# PetSpace

## Histórico de revisão

|**Versão**|**Data**|**Descrição**|**Nome**|
| - | - | - | - |
|1.0|18/04/2021|Criação do documento|Equipe Void|
|2.0|21/04/2021|Revisão do documento perante ao feedback do professor|Equipe Void|
|3.0|26/04/2021|Atualização do Documento de Visão perante a nova metodologia|Bruno Félix|
|4.0|12/05/2021|Revisão Geral|Equipe Void|


## 1. Introdução 

###  1.1 Declaração do problema

|**O problema**|A não praticidade e facilidade de obter produtos e serviços voltados aos pets|
| - | :- |
|**Afeta**|Todos os pets e seus donos|
|**Cujo impacto é**|A pouca diversidade de interação dos donos e seus animais|
|**Uma solução de sucesso seria**|Um e-commerce para a venda de produtos, serviços e adoção de pets|

### 1.2 Objetivo do projeto
<p style="text-align: justify;">
&emsp;&emsp;Criar um e-commerce voltados às necessidades e comodidade dos donos de pets. No meio da pandemia da COVID-19, vários aspectos foram afetados, um deles foi a livre circulação, tornando a compra pela internet, além de uma medida de segurança, prático. Com isso percebemos a oportunidade de criar uma loja virtual para que pessoas consigam comprar produtos e serviços focados para seus pets.
</p>


## 2. Stakeholders

|**Nome**|**Descrição**|**Responsabilidade**|
| - | - | - |
|Usuário|Donos dos animais de estimação|Consumir os produtos, serviços e adotar animais|
|Equipe de Desenvolvimento|Estudantes da disciplina de Requisitos de Software da UnB|Documentar, desenvolver e implementar a aplicação elaborada|
|Administrador|Membro da administração|Responsável por gerenciar a plataforma|
|Professor Orientador|Professor da disciplina Requisitos de Software|   Avaliar e gerar feedback sobre projeto|


## 3. Visão geral do produto

### 3.1 Declaração de posição do produto

|**Para**|Donos de Pets|
| - | - |
|**Quem**|Necessitam comprar produtos, agendar serviços voltado aos pets, adotar um novo pet|
|**O PetSpace**|É um e-commerce|
|**Que**|Busca fornecer praticidade e facilidade na compra de produtos, serviços e adoção de animais|
|**Ao contrário**|Da Petz, que somente faz venda de produtos|
|**Nosso produto**|Além da venda de produtos, fornece a oferta de serviços e adoção de pets|


## 4. Necessidades

|**Necessidade**|**Prioridade**|**Problema**|**Solução Atual**| **Solução Proposta** |
| - | - | - | - | - |
| Realizar compras de produtos e serviços para pets | Alta | Falta de praticidade e facilidade na compra | Geralmente a compra é feita em lojas físicas | Compras online, aumentar a praticidade e facilidade na compra |
| Avaliar produtos e serviços | Média | A falta de feedback dificulta na tomada de decisão da compra | Busca opiniões de terceiros ou em outras fontes | O usuário dá seu feedback sobre um produto ou serviço |
| Realizar adoção de pets | Baixa | Dificuldade de encontrar as diversas opções de adoção | Ir em um local específico para realizar uma adoção | Centralizar as opções de adoção, facilitando a busca e o contato |


## 5. Casos de uso

### 5.1 Requisitos

|Requisito|Nome| Descrição |
| - | - | - |
|Req. 1| Conta | Cliente pode criar e editar sua conta na loja|
|Req. 2| Autenticação| Verificação de dados no sistema |
|Req. 3| Busca | Pesquisa de produtos ou serviços no sistema por nome ou parte do nome |
|Req. 4| Listagem | Listar produtos ou serviços |
|Req. 5| Filtro| Listar produtos ou serviços por categoria|
|Req. 6| Compra | O cliente pode comprar um produto e/ou serviço na loja |
|Req. 7| Avaliação| O cliente tem possibilidade de avaliar um produto ou/e serviço|
|Req. 8| Adoção | O cliente pode contactar a uma instituição |
|Req. 9| Detalhes|É possivel visualizar detalhes dos produtos e serviços, sendo cliente  |
|Req. 10| Cadastro | O administrador pode cadastrar um produto, serviço e instuição no sistema |
|Req. 11| Edição | O administrador pode editar um produto, serviço e/ou instuição cadastrado no sistema |
|Req. 12| Exclusão | O administrador pode excluir um produto, serviço e/ou instuição cadastrado no sistema |
|Req. 13| Compartilhamento| O Cliente consegue encaminhar qualquer produto, serviço e/ou instituição de adoção|



### 5.2 Casos de uso

| ID |Requisito|Caso de Uso|Atores|
|-| - | - | - |
| CS1 | Req. 2,Req. 3, Req. 4, Req. 5, Req.  6, Req. 9 |Comprar Produto |Cliente|
| CS2 | Req. 3, Req. 3, Req. 4, Req. 5, Req. 6, Req. 9|Comprar Serviço |Cliente|
| CS3 | Req. 3, Req. 6|Finalizar Compra |Cliente|
| CS4 | Req. 8 |Adotar Pet|Cliente|
| CS5 | Req. 2|Fazer Login|Cliente|
| CS6 | Req. 1|Criar Conta|Cliente|
| CS7 | Req. 2, Req. 7|Avaliar Produto |Cliente|
| CS8 | Req. 2, Req. 7|Avaliar Serviço |Cliente|
| CS9 | Req. 2, Req. 7|Fazer Comentário da Instituição de Adoção de Pet |Cliente|
| CS10| Req. 13 |Compartilhar em Redes Sociais| Cliente |    
| CS11 | Req. 10 |Cadastrar Produto|Administrador|
| CS12 | Req. 10 |Cadastrar Serviço|Administrador|
| CS13 | Req. 10 |Cadastrar Instituição de Adoção de Pet|Administrador|
| CS14 | Req. 11 |Editar Produto|Administrador|
| CS15 | Req. 11 |Editar Serviço|Administrador|
| CS16 | Req. 11 |Editar Instituição de Adoção de Pet|Administrador|
| CS17 | Req. 12 |Excluir Produto|Administrador|
| CS18 | Req. 12 |Excluir Serviço|Administrador|
| CS19 | Req. 12 |Excluir Instituição de Adoção de Pet|Administrador|

### 5.3 Mínimo produto viável (MVP)

- Fazer adoção;
- Fazer avaliação de produto;
- Compartilhar em redes sociais


## 6. Diagrama de caso de uso

![](https://raw.githubusercontent.com/Bruno-Felix/REQ-2020.2-PetSpace/gh-page/images/Use-case.png)


## 7. Visão geral do projeto

### 7.1 Organização do projeto

|**Papel**|**Atribuição**|**Responsável**|
| - | - | - |
|Professor|Orientar e resolver problemas em última instância.|George|
|Time de Desenvolvimento|É a equipe de profissionais responsável por transformar os Casos de Uso em um produto funcional.|Bruno Félix, Daniel Primo, Francisco Ferreira e Pedro Henrique|


## 8. Ferramentas, ambiente e infraestrutura

|**Ferramentas**|**Descrição**|
| - | - |
|WordPress|É um sistema livre e aberto de gestão de conteúdo para internet, baseado em PHP com banco de dados MySQL, executado em um servidor interpretador|
|MySQL|É um sistema de gerenciamento de banco de dados, que utiliza a linguagem SQL como interface.|
|phpMyAdmin|É um aplicativo web livre e de código aberto desenvolvido em PHP para administração do MySQL pela Internet.|
|Docker|É um conjunto de produtos de plataforma como serviço que usam virtualização de nível de sistema operacional para entregar software em pacotes chamados contêineres.|
|Heroku|É uma plataforma em nuvem como um serviço que suporta várias linguagens de programação.|
|Travis CI|É um serviço de integração contínua hospedado usado para construir e testar projetos de software hospedados no GitHub e Bitbucket.|
|Dockerhub|É um repositório público onde empresas podem publicar suas soluções em forma de imagem|
|GitHub|É uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git.|


## 9. Processo de gerência de projeto

### 9.1 Planejamento das fases e iterações do projeto

|**Reunião**|**Data**|**Descrição**|
| - | - | - |
|Reunião 4|06/abr a 22/abr|Organização estrutural dos requisitos Definição do Produto|
|Reunião 5|27/abr a 13/mai|Definição do Escopo da Iteração Gerenciamento dos Requisitos|


### 9.2 Processos de desenvolvimento e mensuração

<p style="text-align: justify;">&emsp;&emsp; 
&emsp;&emsp;O processo de desenvolvimento da aplicação será conduzido por meio das etapas do Processo Unificado, orientando a Casos de Uso. Na primeira fase que é a concepção: o objetivo desta fase é levantar o escopo do projeto, uma visão primária dos problemas. Já na fase de Elaboração, os requisitos são especificados em detalhes, baseando-se nos seus riscos e valores arquiteturais. Na fase de Construção os elementos serão implementados. For fim na fase de Transição é onde acontece testes finais e a implantação.
</p>

<p style="text-align: justify;">&emsp;&emsp; 
&emsp;&emsp;Nosso processo de mensuração, no planejamento do Projeto, será feito por parte do processo de Inspeção. Através do planejamento, apresentação, preparação, reunião, correção e acompanhamento, podesse verificar o produto de trabalho e encontrar os erros para serem corrigidos.
</p>

### 9.3 Matriz de comunicação

|**Comunicação**|**Proposta**|**Meio**|**Frequência**|**Participantes**|
| - | - | - | - | - |
| Reunião de iniciação | Definir prazos e objetivos | Vídeo-chamada através do Microsoft Teams | Ao início de cada unidade | Time de desenvolvimento e professor |
| Reunião do time de desenvolvimento | Comunicar o andamento do desenvolvimento | Vídeo-chamada através do Jitsi Meet | Semanalmente | Time de desenvolvimento |
| Reunião de relatório do projeto | Analisar os resultados do projeto | Vídeo-chamada através do Jitsi Meet | Mensalmente | Time de desenvolvimento |
| Reunião de problemas técnicos | Comunicar algum impedimento ou problema técnico | Vídeo-chamada através do Jitsi Meet | Quando necessário | Time de desenvolvimento |
| Reunião de encerramento de unidade | Apresentar os resultados desenvolvidos e receber o feedback | Vídeo-chamada através do Microsoft-teams | Ao fim de cada unidade | Time de desenvolvimento e professor |

### 9.4 Gerenciamento de risco

|**ID**|**Descrição**|**Ação**|
| - | - | - |
|RS01|Dificuldades da equipe com as tecnologias inseridas|Realização uma reunião técnica durante o desenvolvimento do projeto para a melhor performance|
|RS02|Erros durante o planejamento das atividades|Utilização de ferramentas de fluxo de trabalho para planejar|
|RS03|Má elicitação dos requisitos|Uso de estratégias de elicitação de requisitos usadas no Processo Unificado|
|RS04|Falta de alinhamento entre a equipe|Encontros através de reuniões|
|RS05|Conflito com outras atividades acadêmicas|Uso de planejamento de horário através de cada sprint, para o melhor aproveitamento das horas para a matéria|
|RS06|Desistência da disciplina|Incentivar a participação dos membros e a união do time. Redistribuir tarefas e refazer parte do planejamento do projeto|
|RS07|Problemas pessoais ou de saúde relacionados a pandemia da COVID-19|Seguir as recomendações de prevenção da Organização Mundial da Saúde e remanejamento das atividades e apoio ao(s) membro(s) afetado(s)|
|RS08|Problemas com a estação de trabalho|Remanejamento das atividades e revisão do cronograma|
|RS09|Alteração do escopo|Refinar constantemente os requisitos e manter as funcionalidades atualizadas e redefinir o escopo e redistribuir tarefas|
|RS10|Divergência de horários entre membros da equipe|Planejar os horários e reuniões baseado na planilha de horários|
|RS11|Falta de interação entre a equipe|Chamar os membros para alguma atividade divertida fora do contexto da disciplina|


### 9.5 Critérios de replanejamento

Ter bem definido os critérios de replanejamento assegurará uma boa entrega do produto, levantamos 3 que serão cruciais no projeto.

- Mudança de visão do projeto: Ao debater sobre uma funcionalidade, ou conversar com o cliente e entender melhor suas necessidades, podem haver novas perspectivas sobre o que o projeto deveria ser, havendo assim, a necessidade de replanejar e realinhar a visão do projeto;
- Mudança de escopo do produto: Baseado numa mudança de visão, ou por um curto espaço de tempo hábil para o desenvolvimento, talvez se mostre necessário replanejar que será entregue;
- Poucas entregas: Ao final de cada Inspeção será feita uma reunião de revisão, pode-se notar uma diferença grande entre o planejado e o entregue. Isso pede que no próximo planejamento seja levantado o que deu errado e o que pode ser feito para que as entregas passadas sejam feitas e que as novas sejam bem desenvolvidas, dentro do prazo e do planejamento.


## 10. Lições aprendidas

<p style="text-align: justify;">&emsp;&emsp; 
&emsp;&emsp; Sobre a metodologia de ensino do processo unificado, foi de bom proveito para todos do grupo. Pelo fato do processo unificado ser baseado em UML, utilizamos para padronizar nossos documentos e entregas, e foi muito importante para nosso aprendizado na matéria de requisitos em geral. Sabendo disso, hoje temos uma melhor perspectiva sobre o trabalho, comparado com o início, e isso foi trazido também pelo fato de estar sendo vivenciada a metodologia do processo unificado. Diferentemente do ágil, o processo unificado nos trouxe um outro olhar na ação de levantamento de requisitos.
</p>


## 11. Referências 

* Wazlawick, Raul Sidnei. Engenharia de software: conceitos e práticas. Rio de Janeiro: Elsevier, 2013.
* Kendall Scott – O Processo Unificado Explicado, Bookman, 2003.
* LARMAN, CRAIG – Utilizando UML e Padrões, 3a edição, Bookman, 2007.
