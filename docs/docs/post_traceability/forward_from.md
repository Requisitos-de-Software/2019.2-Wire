# Forward from

|    Data    | Versão |      Descrição       |           Autor(es)            |
| :--------: | :----: | :------------------: | :----------------------------: |
| 17/11/2019 |  1.0   | Criação do documento | Guilherme Mendes, João Pedro e Lucas Fellipe |

## Rastreabilidade
[Histórias de Usuário](/docs/post_traceability/user_stories.md)

## Tabela Forward from

| Tema | Épico | Feature | ID   | Descrição                                       | História de Usuário      | Telas     |
|:----:|:-----:|:-------:|:----:|:-----------------------------------------------:|:------------------------:|:---------:|
| T01  | E01   | EF01    | RF01 | Enviar mensagem                                 | US01                     | GIF  |
| T01  | E01   | EF01    | RF02 | Definir quanto tempo a mensagem fica visível    | US01                     | GIF  |
| T01  | E01   | EF01    | RF03 | Apagar mensagem                                 | US01                     | GIF  |
| T01  | E01   | EF01    | RF04 | Responder mensagem                              | US01                     | GIF  |
| T01  | E01   | EF01    | RF05 | Encaminhar mensagem                             | US01                     | GIF  |
| T01  | E01   | EF01    | RF06 | Editar mensagem                                 | US01                     | GIF  |
| T01  | E01   | EF01    | RF07 | Enviar áudio                                    |                          | GIF  |
| T01  | E01   | EF01    | RF08 | Apagar áudio                                    | US05                     | GIF  |
| T01  | E01   | EF01    | RF09 | Selecionar mensagens                            | US01                     | GIF Protótipo |
| T01  | E01   | EF01    | RF10 | Dar play e pause no áudio                       | US05                     | GIF  |
| T01  | E01   | EF01    | RF11 | Escolher ponto de tempo do áudio                | US05                     |           |
| T01  | E01   | EF01    | RF12 | Enviar imagem e vídeo                           | US05                     | GIF  |
| T01  | E01   | EF01    | RF13 | Editar imagem                                   | US05                     | GIF  |
| T01  | E01   | EF01    | RF14 | Enviar arquivo                                  | US02                     | GIF  |
| T01  | E01   | EF01    | RF15 | Download de arquivos                            | US02                     | GIF  |
| T01  | E01   | EF01    | RF16 | Abrir arquivo dentro do aplicativo              | US02                     | GIF  |
| T01  | E01   | FE03    | RF17 | Chamada de vídeo                                | US06                     |           |
| T01  | E01   | FE03    | RF18 | Adicionar pessoas à chamada de vídeo            | US06                     |           |
| T01  | E01   | FE03    | RF19 | Entrar em chamada de vídeo já existente         | US06                     | GIF  |
| T01  | E01   | FE03    | RF20 | Ligar e desligar câmera                         | US06                     |           |
| T01  | E01   | FE03    | RF21 | Fazer ligação de áudio                          | US05                     | GIF  |
| T01  | E01   | FE03    | RF22 | Ligar e desligar microfone                      | US05, US06               | GIF  |
| T01  | E01   | FE03    | RF23 | Sair da chamada                                 | US05, US06               | GIF  |
| T01  | E01   | FE02    | RF24 | Criar grupo                                     | US03, US04               | GIF  |
| T01  | E01   | FE02    | RF25 | Adicionar pessoas no grupo                      | US03, US04               | GIF  |
| T01  | E01   | FE02    | RF26 | Remover pessoas do grupo                        | US04                     | GIF  |
| T01  | E01   | FE02    | RF27 | Definir permissões de cada membro do grupo      | US04                     | GIF Protótipo |
| T01  |       |         | RF28 | Responder mensagem recebida no grupo no privado | US01                     | GIF Protótipo |
| T01  |       |         | RF29 | Fixar mensagens                                 | US01                     | GIF Protótipo |
| T01  |       |         | RF30 | Mensagem de alerta                              | US01                     | GIF  |
| T01  |       |         | RF31 | Silenciar grupo                                 | US03                     | GIF  |
| T01  |       |         | RF32 | Criar canal de transmissão de mensagens         | US01                     |           |
| T01  |       |         | RF33 | Criar Guest Room                                |                          |           |
| T01  |       |         | RF34 | Adicionar contatos                              | New user story           |           |
| T01  |       |         | RF35 | Editar dados do contato                         | New user story           |           |
| T01  |       |         | RF36 | Bloquear usuário                                | New user story           | GIF  |
| T01  | E01   | FE02    | RF37 | Criar time                                      | US04 e US03              | GIF  |
| T01  | E01   | FE02    | RF38 | Adicionar usuários ao seu time                  | US04                     |           |
| T01  | E02   | FE04    | RF39 | Cadastrar usuário pelo número                   | US07                     |           |
| T01  | E02   | FE04    | RF40 | Cadastrar usuário pelo e-mail                   | US07                     |           |
| T01  | E02   | FE04    | RF41 | Definir nome do usuário                         | US08                     | GIF  |
| T01  | E02   | FE04    | RF42 | Editar perfil                                   | US08                     | GIF  |
| T01  | E02   | FE05    | RF43 | Alterar opção de fazer download automático      | Não existe no aplicativo |           |
| T01  | E02   | FE05    | RF44 | Mudar senha                                     | US09                     | GIF  |
| T01  | E02   | FE05    | RF45 | Fazer Backup                                    | US09                     | GIF  |
| T01  | E02   | FE05    | RF46 | Deletar conta                                   | US09                     | GIF  |

## Requisitos Funcionais
### RF01 - Enviar mensagem
* **Tema** - Aplicativo de comunicação.
* **Épico** - Comunicação entre usuários.
* **Feature** - Chat de mensagem.
* **Rastreabilidade** - [RF01](/docs/elicitation/matrix?id=rf01)
* **História de Usuário** - [US01](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/send_message.gif" width=47%>
    
### RF02 - Definir quanto tempo a mensagem fica visível
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF02](/docs/elicitation/matrix?id=rf02)
* **História de Usuário** - [US01](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/define_message_time.gif" width=47%>
    
### RF03 - Apagar mensagem
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF03](/docs/elicitation/matrix?id=rf03)
* **História de Usuário** - [US01](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/delete_message.gif" width=47%>
    

### RF04 - Responder mensagem
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF04](/docs/elicitation/matrix?id=rf04)
* **História de Usuário** - [US01](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/answer_message.gif" width=47%>

### RF05 - Encaminhar mensagem
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF05](/docs/elicitation/matrix?id=rf05)
* **História de Usuário** - [US01](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/forward_message.gif"  width=47%>

### RF06 - Editar mensagem
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF06](/docs/elicitation/matrix?id=rf06)
* **História de Usuário** - [US01](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/edit_message.gif"  width=47%>

### RF07 - Enviar áudio
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF07](/docs/elicitation/matrix?id=rf07)
* **História de Usuário** - [US13](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/record_audio.gif"  width=47%>


### RF08 - Apagar áudio
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF08](/docs/elicitation/matrix?id=rf08)
* **História de Usuário** - [US13](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/delete_audio.gif" width=47%>

### RF09 - Selecionar mensagens
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF09](/docs/elicitation/matrix?id=rf09)
* **História de Usuário** - [US01](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/select_message.gif" width=47%>

### RF10 - Dar play e pause no áudio
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF10](/docs/elicitation/matrix?id=rf10)
* **História de Usuário** - [US13](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/play_audio.gif" width=47%>

### RF11 - Escolher ponto de tempo do áudio
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF11](/docs/elicitation/matrix?id=rf11)
* **História de Usuário** - [US13](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/delete_audio.gif" width=47%>

### RF12 - Enviar imagem/vídeo
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF12](/docs/elicitation/matrix?id=rf12)
* **História de Usuário** - [US02](/)
* **Funcionalidade**

<img src="docs/assets/img/post_traceability/send_image.gif" width=47%>

<img src="docs/assets/img/post_traceability/send_video.gif" width=47%>

### RF13 - Editar imagem
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF13](/docs/elicitation/matrix?id=rf13)
* **História de Usuário** - [US02](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/edit_image.gif" width=47%>

### RF14 - Enviar arquivo
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF14](/docs/elicitation/matrix?id=rf14)
* **História de Usuário** - [US02](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/send_file.gif" width=47%>

### RF15 - Download de arquivos
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF15](/docs/elicitation/matrix?id=rf15)
* **História de Usuário** - [US02](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/download_file.gif" width=47%>

### RF16 - Abrir arquivo dentro do aplicativo
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF16](/docs/elicitation/matrix?id=rf16)
* **História de Usuário** - [US02](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/open_file.gif" width=47%>

### RF17 - Chamade de vídeo
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Ligação direta entre usuários;
* **Rastreabilidade** - [RF17](/docs/elicitation/matrix?id=rf17)
* **História de Usuário** - [US06](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/video_call.gif" width=47%>

### RF18 - Adicionar pessoas à chamada de vídeo
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Ligação direta entre usuários;
* **Rastreabilidade** - [RF18](/docs/elicitation/matrix?id=rf18)
* **História de Usuário** - [US06](/)
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/delete_audio.gif" width=47%> ADICIONAR VÍDEO -->

### RF19 - Entrar em chamada de vídeo já existente
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Ligação direta entre usuários;
* **Rastreabilidade** - [RF19](/docs/elicitation/matrix?id=rf19-arroz)
* **História de Usuário** - [US06](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/join_existing_call.gif" width=47%>

### RF20 - Ligar e desligar câmera
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Ligação direta entre usuários;
* **Rastreabilidade** - [RF20](/docs/elicitation/matrix?id=rf20)
* **História de Usuário** - [US06](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/turn_off_camera.gif" width=47%>

### RF21 - Fazer ligação de áudio
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Ligação direta entre usuários;
* **Rastreabilidade** - [RF21](/docs/elicitation/matrix?id=rf21)
* **História de Usuário** - [US05](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/audio_call.gif" width=47%>

### RF22 - Ligar e desligar microfone
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Ligação direta entre usuários;
* **Rastreabilidade** - [RF22](/docs/elicitation/matrix?id=rf22)
* **História de Usuário** - [US05](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/mute_call.gif" width=47%>

### RF23 - Sair da chamada
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Ligação direta entre usuários;
* **Rastreabilidade** - [RF23](/docs/elicitation/matrix?id=rf23)
* **História de Usuário** - [US05](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/turn_off_call.gif" width=47%>

### RF24 - Criar grupo
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Equipes;
* **Rastreabilidade** - [RF24](/docs/elicitation/matrix?id=rf24)
* **História de Usuário** - [US04](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/group_creation.gif" width=47%>

### RF25 - Adicionar pessoas no grupo
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Equipes;
* **Rastreabilidade** - [RF25](/docs/elicitation/matrix?id=rf25)
* **História de Usuário** - [US04](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/add_contacts_to_group.gif" width=47%>

### RF26 - Remover pessoas do grupo
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Equipes;
* **Rastreabilidade** - [RF26](/docs/elicitation/matrix?id=rf26)
* **História de Usuário** - [US04](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/group_remove.gif" width=47%>

### RF27 - Definir permissōes de cada membro do grupo
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Equipes;
* **Rastreabilidade** - [RF27](/docs/elicitation/matrix?id=rf27)
* **História de Usuário** - [US03](/)
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/delete_audio.gif" width=47%> ADICIONAR VÍDEO -->

### RF28 - Responder mensagem recebida no grupo no privado
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem; <!-- Definir melhor -->
* **Rastreabilidade** - [RF28](/docs/elicitation/matrix?id=rf28)
* **História de Usuário** - [US01](/) <!-- Definir melhor -->
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/delete_audio.gif" width=47%>
    ADC VÍDEO -->

### RF29 - Fixar mensagens
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem;
* **Rastreabilidade** - [RF29](/docs/elicitation/matrix?id=rf29)
* **História de Usuário** - [US01](/)
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/delete_audio.gif" width=47%> ADICIONAR VÍDEO -->

### RF30 - Mensagem de alerta
* **Tema** - Aplicativo de comunicação;
* **Épico** - Comunicação entre usuários;
* **Feature** - Chat de mensagem; <!-- Definir melhor -->
* **Rastreabilidade** - [RF30](/docs/elicitation/matrix?id=rf30)
* **História de Usuário** - [US01](/)
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/message_notification.gif" width=47%> ADICIONAR VÍDEO

### RF31 - Silenciar grupo
* **Tema** - 
* **Épico** - 
* **Feature** - 
* **Rastreabilidade** - [RF31](/docs/elicitation/matrix?id=rf31)
* **História de Usuário** - 
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/silence_group.gif" width=47%>

### RF32 - Criar canal de transmissão de mensagens
* **Tema** - 
* **Épico** - 
* **Feature** - 
* **Rastreabilidade** - [RF32](/docs/elicitation/matrix?id=rf32)
* **História de Usuário** - 
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/delete_audio.gif" width=47%> -->

### RF33 - Criar Guest Room
* **Tema** - 
* **Épico** - 
* **Feature** - 
* **Rastreabilidade** - [RF33](/docs/elicitation/matrix?id=rf33)
* **História de Usuário** - 
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/delete_audio.gif" width=47%> -->


### RF34 - Adicionar contatos
* **Tema** - 
* **Épico** - 
* **Feature** - 
* **Rastreabilidade** - [RF34](/docs/elicitation/matrix?id=rf34)
* **História de Usuário** - 
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/delete_audio.gif" width=47%> -->

### RF35 - Criar Guest Room
* **Tema** - 
* **Épico** - 
* **Feature** - 
* **Rastreabilidade** - [RF35](/docs/elicitation/matrix?id=rf35)
* **História de Usuário** - 
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/delete_audio.gif" width=47%> -->


### RF36 - Bloquear usuário
* **Tema** - 
* **Épico** - 
* **Feature** - 
* **Rastreabilidade** - [RF36](/docs/elicitation/matrix?id=rf36)
* **História de Usuário** - 
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/block_user.gif" width=47%>

### RF37 - Criar time
* **Tema** - Aplicativo de comunicação
* **Épico** - Comunicação entre usuários
* **Feature** - Equipes
* **Rastreabilidade** - [RF37](/docs/elicitation/matrix?id=rf37)
* **História de Usuário** - [US03]() 
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/group_creation.gif" width=47%>


### RF38 - Adicionar usuários ao seu time
* **Tema** - Aplicativo de comunicação
* **Épico** - Comunicação entre usuários
* **Feature** - Equipes
* **Rastreabilidade** - [RF38](/docs/elicitation/matrix?id=rf38)
* **História de Usuário** - [US03]()
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/add_contacts_to_group.gif" width=47%>

### RF39 - Cadastrar usuário pelo número
* **Tema** - Aplicativo de comunicação
* **Épico** - Gerenciamento de usuários
* **Feature** - Cadastrar usuário
* **Rastreabilidade** - [RF39](/docs/elicitation/matrix?id=rf39)
* **História de Usuário** - [US07]()
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/group_creation.gif" width=47%> -->

### RF40 - Cadastrar usuário pelo e-mail
* **Tema** - Aplicativo de comunicação
* **Épico** - Gerenciamento de usuários
* **Feature** - Cadastrar usuário
* **Rastreabilidade** - [RF40](/docs/elicitation/matrix?id=rf40)
* **História de Usuário** - [US07]()
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/block_user.gif" width=47%> -->

### RF41 - Definir nome do usuário
* **Tema** - Aplicativo de comunicação
* **Épico** - Gerenciamento de usuários
* **Feature** - Cadastrar usuário
* **Rastreabilidade** - [RF41](/docs/elicitation/matrix?id=rf41)
* **História de Usuário** - [US08]()
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/change_username.gif" width=47%>

### RF42 - Editar perfil
* **Tema** - Aplicativo de comunicação
* **Épico** - Gerenciamento de usuários
* **Feature** - Cadastrar usuário
* **Rastreabilidade** - [RF42](/docs/elicitation/matrix?id=rf42)
* **História de Usuário** - [US08]()
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/edit_profile.gif" width=47%>

### RF43 - Alterar opção de fazer download automático
* **Tema** - Aplicativo de comunicação
* **Épico** - Gerenciamento de usuários
* **Feature** - Definir configurações de conta
* **Rastreabilidade** - [RF43](/docs/elicitation/matrix?id=rf43)
* **História de Usuário** - [US]()
* **Funcionalidade**

    <!-- <img src="docs/assets/img/post_traceability/.gif" width=47%> -->

### RF44 - Mudar senha
* **Tema** - Aplicativo de comunicação
* **Épico** - Gerenciamento de usuários
* **Feature** - Definir configurações de conta
* **Rastreabilidade** - [RF44](/docs/elicitation/matrix?id=rf44)
* **História de Usuário** - [US09]()
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/change_password.gif" width=47%>

### RF45 - Fazer Backup
* **Tema** - Aplicativo de comunicação
* **Épico** - Gerenciamento de usuários
* **Feature** - Definir configurações de conta
* **Rastreabilidade** - [RF45](/docs/elicitation/matrix?id=rf45)
* **História de Usuário** - [US09]()
* **Funcionalidade**

    <img src="docs/assets/img/post_traceability/backup.gif" width=47%>

### RF46 - Deletar conta
* **Tema** - Aplicativo de comunicação
* **Épico** - Gerenciamento de usuários
* **Feature** - Definir configurações de conta
* **Rastreabilidade** - [RF46](/docs/elicitation/matrix?id=rf46)
* **História de Usuário** - [US09]()
* **Funcionalidade**


    <img src="docs/assets/img/post_traceability/delete_account.gif" width=47%>











## História de Usuário

### US01 - Eu, como usuário do sistema, desejo enviar mensagens de texto para me comunicar com outras pessoas.

### US02 - Eu, como usuário do sistema, desejo enviar arquivos para possuir uma possibilidade maior de compartilhamento de dados

### US03 - Eu, como usuário do sistema, desejo criar equipes para um melhor gerenciamento dos meus contatos

### US04 - Eu, como usuário do sistema, desejo ter controle de gerência das minhas equipes para modularizar comunicações internas

### US05 - Eu, como usuário do sistema, desejo fazer ligações de áudio para que eu possa me comunicar em tempo real com outros usuários de forma eficiente

### US06 - Eu, como usuário do sistema, desejo fazer ligações de vídeo para que eu possa mostrar imagens e compartilhar minha tela durante as chamadas

### US07 - Eu, como usuário do sistema, desejo me cadastrar no aplicativo para que eu possa ter acesso as funcionalidades propostas

### US08 - Eu, como usuário do sistema, desejo criar meu perfil pessoas para que eu seja identificado dentro do aplicativo

### US09 - Eu, como usuário do sistema, desejo ter controle das configurações para personalizar dados da minha conta

### US10 - Eu, como usuário do sistema, desejo integrar e utilizar mais funcionalidades para personalizar a aplicação de acordo com as minhas necessidades

### US11 - Eu, como usuário do sistema, desejo criar novos serviços externos para o Wire para adequar a aplicação as minhas necessidades e contribuir com a comunidade de usuários 



<!DOCTYPE html>
<html>
<head>
<style src='docs/docs/assets/css/table.css'>
table {
  width: 100%;
}
</style>
<link rel="stylesheet" href="docs/assets/css/table.css">
</head>
</html> 