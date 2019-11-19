# Módulo de Usuários

## Diagrama de casos de uso

<img src="docs/assets/img/modeling/uc_diagrams/UserCasesDiagram_Wire_Usuarios.png">

<p align="right">
<a href="https://user-images.githubusercontent.com/42645264/66132062-ddde5200-e5ca-11e9-93ac-1169ef9e4577.png"> Clique aqui para visualizar a imagem ampliada.
</p>

## Especificações dos casos de uso

|Casos de Uso|Ator|Descrição|
|---|---|------|
|UC37 - Conectar em uma conta existente | Esse caso de uso ocorre quando um usuário, previamente cadastrado, entra em sua conta do Wire|
|UC38 - Adicionar contato de usuário| Usuário | Esse caso de uso fornece ao usuário a opção de salvar o número, nome de usuário e e-mail de outro usuário|
|UC39 - Editar dados do contato| Usuário | Esse caso de uso permite o usuário editar os dados de contatos salvos na plataforma operante|
|UC40 - Bloquear usuário| Usuário | Esse caso de uso possibilita ao usuário bloquear o acesso de outro usuário a ele|
|UC41 - Editar perfil| Usuário | Esse caso de uso permite o usuário alterar os dados inseridos em seu perfil|
|UC42 - Alterar opção de download automático| Usuário | Esse caso de uso ocorre quando o usuário desativa o download automático de arquivos, imagens, vídeos e/ou áudios|
|UC43 - Deletar conta| Usuário | Esse caso de uso permite que o usuário delete sua conta atual|
|UC44 - Mudar senha| Usuário | Esse caso de uso possibilita ao usuário mudar a senha de login da conta atual|
|UC45 - Fazer backup de mensagens| Usuário | Este caso de uso possibilita o usuário salvar, em um banco de dados próprio, todas as conversas do aplicativo |

## Fluxo de Eventos

### **UC37 - Conectar em uma conta existente**
| |
| - |
| <h3> Fluxo Básico </h3> |
| Usuário 1 acessa sua conta wire a partir do email e senha cadastrados
| <h3> Fluxos Alternativos </h3> |
| <h4><b> FA1 - Adicionar e editar dados de contato de um usuário </b></h4> |
| O usuário 1, após acessar sua conta, salva os dados do usuário 2 no aplicativo, a partir do e-mail do usuário 2 e altera os dados salvos do usuário 2, muda o nome com o qual o contato estava salvo |
| <h4><b> FA2 - Bloquear usuário </b></h4> |
| O usuário 1, após acessar sua conta, bloqueia um usuário desconhecido que o mandou spans de sorteios |
| <h4><b> FA3 - Editar perfil </b></h4> |
| O usuário 1, após acessar sua conta, alterou sua foto de perfil, pois a anterior era uma foto antiga |
| <h4><b> FA4 - Alterar opção de download automático </b></h4> |
| O usuário 1 está com pouca memória no celular e não quer mais baixar as imagens que recebe no aplicativo, para isso ele altera a opção de download automático, após acessar sua conta |
| <h4><b> FA5 - Deletar conta </b></h4> |
| Usuário 1 não pretende mais utilizar o Wire e, após acessar sua conta, a deleta |
| <h4><b> FA6 - Mudar senha </b></h4> |
| Usuário 1, por motivos de segurança, altera a senha de sua conta mensalmente, sempre efetuando o cadastro antes da alteração |
| <h4><b> FA7 - Fazer backup de mensagens </b></h4> |
| O usuário 1, após acessar sua conta, faz o backup das conversas que possui no aplicativo, salvando-as no Desktop pessoal dele |