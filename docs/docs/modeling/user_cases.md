<!DOCTYPE html>
<html>
<head>
<style>
    div.polaroid {
    width: 1100px;
    height: 400px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    text-align: center;
    }
    div.container {
    padding: 10px;
    }
</style>
</head>
<body>

# Casos de Uso

### Diagrama de casos de uso

<br>
<div class="polaroid">
<img src="https://i.imgur.com/MwkPOuS.png/" width=100% height=400px>
</div>


### Especificações dos casos de uso

|Casos de Uso|Ator|Descrição|
|---|---|------|
|UC01 - Enviar mensagem| Usuário | Este caso de uso ocorre quando o usuário envia uma mensagem de texto ou de áudio para outro usuário|
|UC02 - Apagar mensagem| Usuário| Este caso de uso permite que o usuário apague uma mensagem enviada anteriormente|
|UC03 - Editar mensagem| Usuário | Este caso de uso ocorre quando o usuário deseja editar uma mensagem enviada|
|UC04 - Enviar arquivos| Usuário | Este caso de uso possibilita o usuário enviar arquivos externos, como .jpg, .pdf, entre outros tipos|
|UC05 - Fazer ligação| Usuário | Esse caso de uso permite o usuário se comunicar por meios além da mensagem|
|UC06 - Fazer ligação de vídeo| Usuário | Esse caso de uso fornece ao usuário a opção de ter uma conversa por vídeo com outro usuário|
|UC07 - Fazer ligação de áudio| Usuário | Esse caso permite ao usuário a opção de ter uma conversa por áudio com outro usuário|
|UC08 - Adicionar pessoas à chamada| Usuário | Este caso de uso ocorre quando o usuário adiciona uma terceira pessoas à chamada atual, seja de áudio ou de vídeo|
|UC09 - Criar grupo| Usuário| Este caso de uso permite que o usuário crie um grupo com outros usuários para que possam trocar mensagens|
|UC10 - Adicionar e remover pessoas do grupo| Usuário | Este caso de uso possibilita o usuário controlar as pessoas que estão no grupo|
|UC11 - Definir permissões de cada membro| Usuário | Esse caso de uso permite o usuário que criou o grupo definir as ações que outros membros do grupo podem executar|
|UC12 - Adicionar contatos| Usuário | Esse caso de uso fornece ao usuário a opção de salvar o número, nome de usuário e e-mail de outro usuário|
|UC13 - Editar dados do contato| Usuário | Esse caso permite ao usuário editar os dados de contatos salvos na plataforma operante|
|UC14 - Cadastrar usuário| Usuário | Esse caso de uso ocorre quando o usuário começa a usar o aplicativo e se cadastra pela primeira vez no mesmo, criando uma conta. É possível ter mais de uma conta|
|UC15 - Cadastrar por número de telefone| Usuário | Esse caso de uso fornece ao usuário a opção se cadastrar a partir do número de telefone utilizado|
|UC16 - Cadastrar por endereço de e-mail| Usuário | Esse caso de uso fornece ao usuário a opção se cadastrar a partir de um endereço de e-mail|


### Fluxo de Eventos

### UC01 - Enviar Mensagem
#### Fluxo Básico

Usuário 1 envia uma mensagem de texto para o usuário 2

#### Fluxos Alternativos

#### FA1 - Apagar mensagem

Usuário 1 envia uma mensagem de texto para o usuário 2 e após algum tempo apaga a mensagem

#### FA2 - Editar mensagem

Usuário 1 envia uma mensagem de texto para o usuário 2 e depois edita o que estava escrito na mensagem

#### FA3 - Enviar arquivo

Usuário 1 envia uma mensagem que possui um arquivo no formato PDF para o usuário 2

### UC05 - Fazer ligação
#### Fluxo Básico

Usuário 1 liga para o usuário 2, seja por áudio ou por vídeo

#### Fluxos Alternativos

#### FA1 - Fazer ligação de vídeo

Usuário 1 liga por vídeo para o usuário 2

#### FA2 - Fazer ligação de áudio

Usuário 1 liga por áudio para o usuário 2

#### FA3 - Adicionar pessoas à chamada

Usuário 1 está em uma ligação de vídeo com o usuário 2 e adiciona o usuário 3 à chamada

### UC09 - Criar grupo
#### Fluxo Básico

Usuário 1 um grupo vazio no aplicativo


#### Fluxos Alternativos

#### FA1 - Adicionar e remover pessoas do grupo

Usuário 1 adiciona o usuário 2 e o usuário 3 no grupo

#### FA2 - Definir permissões de cada membro

Usuário 1 aumenta as permissões do usuário 2, para que ele tenha mais autorizações no grupo


### UC12 - Adicionar contatos
#### Fluxo Básico

Usuário 1 salva os dados do usuário 2 no aplicativo, a partir do e-mail do usuário 2

#### Fluxos Alternativos

#### FA1 - Editar dados do contato

Usuário 1 altera os dados salvos do usuário 2 e muda o nome com o qual o contato estava salvo


### UC14 - Cadastrar usuário
#### Fluxo Básico

Usuário 1 entra no aplicativo pela primeira vez e faz seu cadastro a partir do número de telefone utilizado

#### Fluxos Alternativos

#### FA1 - Cadatrar por endereço de e-mail

Usuário 1 entra no aplicativo pela primeira vez e faz seu cadastro a partir de um endereço de e-mail
