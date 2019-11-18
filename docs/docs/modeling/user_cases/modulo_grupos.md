# Módulo de Grupos
## Diagrama de casos de uso

<img src="docs/assets/img/modeling/uc_diagrams/UserCasesDiagram_Wire_Grupos.png">

<p align="right">
<a href="https://user-images.githubusercontent.com/42645264/68998137-0ecdca00-088d-11ea-8e77-f75c3f73a947.png"> Clique aqui para visualizar a imagem ampliada.
</p>


## Especificações dos casos de uso

|Casos de Uso|Ator|Descrição|
|---|---|------|
|UC21 - Criar grupo| Usuário| Este caso de uso permite que o usuário crie um grupo com outros usuários para que possam trocar mensagens|
|UC22 - Fazer um grupo de Transmissão de mensagens| Usuário| Este caso de uso possibilita que o usuário transforme o grupo criado em um grupo de Transmissão de mensagens, ou seja, apenas pessoas com permissão podem enviar mensagens nele|
|UC23 - Adicionar e remover pessoas do grupo| Usuário | Este caso de uso fornece ao usuário o poder de adicionar e retirar as pessoas do grupo|
|UC24 - Definir permissões de cada membro| Usuário | Esse caso de uso permite o usuário que criou o grupo definir as ações que outros membros do grupo podem executar|
|UC25 - Fixar mensagens| Usuário | Esse caso de uso possibilita o usuário fixar um mensagem no topo do grupo, deixando-a visível para todos|
|UC26 - Silenciar grupo| Usuário | Esse caso de uso permite o usuário silenciar um grupo e não receber notificações do mesmo|
|UC27 - Enviar mensagem de alerta| Usuário | Esse caso de uso disponibiliza ao usuário uma mensagem de alerta, que ignora o silenciamento do grupo|
|UC28 - Responder mensagem recebida no grupo no privado| Usuário | Esse caso de uso permite o usuário responder uma mensagem enviada em um grupo diretamente na conversa privada dele com o usuário que a enviou|
|UC29 - Criar Guest Room| Usuário| Este caso de uso permite que o usuário crie Guest Room, que serve como uma extenção do mensageiro para usuários não cadastrados|
|UC30 - Gerar link externo para adicionar usuário| Usuário| Este caso de uso fornece ao usuário um link para que ele possa disponibilizar o Guest Room criado|

## Fluxo de Eventos

### **UC21 - Criar grupo**
| |
| - |
| <h3> Fluxo Básico </h3> |
| Usuário 1 cria um grupo vazio no aplicativo |
| <h3> Fluxos Alternativos </h3> |
| <h4><b> FA1 - Fazer um grupo de Transmissão de mensagens </b></h4> |
| O usuário 1 cria um grupo de transmissão de mensagens para que ele possa passar recados para outros membros da empresa |
| <h4><b> FA2 - Adicionar e remover pessoas do grupo </b></h4> |
| Usuário 1 adiciona o usuário 2 e o usuário 3 no grupo |
| <h4><b> FA3 - Definir permissões de cada membro </b></h4> |
| Usuário 1 aumenta as permissões do usuário 2, para que ele tenha mais autorizações no grupo |
| <h4><b> FA4 - Fixar mensagens </b></h4> |
| Usuário 1 manda uma mensagem sobre um evento importante da empresa e a fixa no grupo, para que todos a vejam |
| <h4><b> FA5 - Silenciar grupo </b></h4> |
| O usuário 2 silencia o grupo de mensagens que possui com seus amigos, pois o mesmo estava emitindo muitas notificações durante seu horário de serviço |
| <h4><b> FA6 - Enviar mensagem de alerta </b></h4> |
| Usuário 1 enviar uma mensagem de alerta no grupo, pois deseja a atenção de todos para a próxima mensagem que será enviada |
| <h4><b> FA7 - Responder mensagem recebida no grupo no privado </b></h4> |
| O usuário 2 responde uma mensagem do usuário 1 diretamente no privado, pois estava em dúvida sobre o que tinha sido dito, mas não queria falar sobre aquilo em público |
| <h4><b> FA8 - Criar Guest Room e gerar link externo para adicionar usuário </b></h4> |
| Usuário 1 cria um Guest Room para que possa ter uma reunião com um cliente que não possui o aplicativo Wire na versão PRO e gera um link web do Guest Room e o envia para seu cliente para que a reunião possa começar |