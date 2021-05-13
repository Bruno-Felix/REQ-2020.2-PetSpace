
# Caso de Uso: **Adotar Pet**

## 1- Breve Descrição
   O presente caso de uso descreve o fluxo de atividades e execução do serviço de adoção. O serviço de adoção consiste na execução de uma comunicação de um usuário do site PetSpace com uma instituição de adoção, tal como a UIPA (União Internacional Protetora dos Animais).
## 2- Atores
   * Administrador 
   * Cliente
    
## 3- Condições Prévias
   * O usuário deve desejar adotar um novo pet.


## 4- Fluxo Básico de Eventos (FBE)
   * 4.1 - Este caso de uso é iniciado quando o usuário tem desejo de adotar um pet, e entrar em contato com uma instituição de adoção.
   * 4.2 - O usuário deve escolher, na página de adoção, qual instituição disponível ele deseja fazer o contato.
   * 4.3 - O usuário seleciona a página desejada
   * 4.4 - O usuário seleciona o site da instituição.
   * 4.5 - O usuário é redirecionado para o site da instituição.
   * 4.6 - O caso de uso é encerrado.
    
## 5- Fluxos Alternativos de Eventos (FAE)
### 5.1 - Fazer comentário
No passo 4.3 do fluxo básico, o usuário deseja fazer um comentário sobre a instituição.
* 5.1.1 - O sistema solicita nome e email do usuário.
* 5.1.2 - O usuário fornece nome e email, e em seguida faz seu comentário.
* 5.1.3 - O sistema solicita a confirmação dos dados e do comentário.
* 5.1.4 - O usuário confirma os dados e comentário.
* 5.1.5 - O caso de uso continua para o passo 4.4.



## 6- Fluxo de Execção de Eventos (FEE)
* 6.1- **FEE-01: Email inválido:** No passo 5.1.1 (FAE) caso o email for inválido, o sitema retorna a messagem: "Email inválido, por favor, insira um email válido para fazer um comentário."

## 7- Regra de Négócio (RN)
Não se aplica.
## 8- Pós-condições
Não se aplica.
## 9- Pontos de Extensão
Não se aplica.









