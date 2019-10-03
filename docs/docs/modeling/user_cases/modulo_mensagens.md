# Módulo de Mensagens

## Diagrama de casos de uso

![User Cases Diagram - Wire (Mensagens)](https://user-images.githubusercontent.com/42645264/66132029-cdc67280-e5ca-11e9-8e62-3859dabc67c0.png)


## Especificações dos casos de uso

|Casos de Uso|Ator|Descrição|
|---|---|------|
|UC01 - Enviar mensagem| Usuário | Este caso de uso ocorre quando o usuário envia uma mensagem de texto ou de áudio para outro usuário|
|UC02 - Responder mensagem| Usuário| Este caso de uso permite que o usuário explicite para qual mensagem anterior a mensagem enviada no momento se refere |
|UC03 - Apagar mensagem| Usuário| Este caso de uso permite que o usuário apague uma mensagem enviada anteriormente|
|UC04 - Definir tempo de visualização da mensagem| Usuário | Este caso de uso permite ao usuário definir um período de tempo no qual a mensagem enviada ficará disponível para os outros usuários|
|UC05 - Enviar áudio | Usuário | Este caso de uso ocorre quando o usuário grava uma mensagem em um áudio e a envia para outro usuário|
|UC06 - Dar play e pause no áudio | Usuário | Este caso de uso permite o usuário parar e continuar a execução de um áudio recebido|
|UC07 - Escolher ponto de início do áudio | Usuário | Este caso de uso possibilita o usuário escolher em qual momento o áudio começará a ser reproduzido, possibilitando, também, avançar e retroceder o mesmo|
|UC08 - Editar mensagem| Usuário | Este caso de uso ocorre quando o usuário deseja editar uma mensagem enviada|
|UC09 - Encaminhar mensagem| Usuário | Este caso de uso permite ao usuário enviar uma mensagem recebida para outro usuário, sem alterar o remetente original|
|UC10 - Enviar arquivos| Usuário | Este caso de uso possibilita o usuário enviar arquivos externos, como .jpg, .pdf, entre outros tipos|
|UC11 - Abrir arquivo dentro do aplicativo| Usuário | Este caso de uso permite ao usuário abrir um arquivo recebido por mensagem sem sair do aplicativo|
|UC12 - Enviar imagem e vídeo| Usuário | Este caso de uso fornece ao usuário a opção de enviar arquivos de imagem e vídeo por mensagem|
|UC13 - Editar imagem| Usuário | Este caso de uso permite ao usuário editar uma imagem que será enviada|
|UC14 - Fazer backup de mensagens| Usuário | Este caso de uso possibilita o usuário salvar, em um banco de dados próprio, todas as conversas do aplicativo|


## Fluxo de Eventos
### **UC01 - Enviar Mensagem**

| |
| - |
| <h3>Fluxo Básico</h3> |
|Usuário 1 envia uma mensagem de texto para o usuário 2|
| <h3>Fluxos Alternativos</h3> |
| <h4><b> FA1 - Responder mensagem </b></h4> |
| Usuário 1 responde uma mensagem que o usuário 2 havia enviado |
| <h4><b> FA2 - Apagar mensagem </b></h4> |
| Usuário 1 envia uma mensagem de texto para o usuário 2 e após algum tempo apaga a mensagem |
| <h4><b>FA3 - Definir tempo de visualização da mensagem</b></h4> |
| Usuário 1 define o tempo de visualização da mensagem para 10 segundos e envia um texto para o usuário 2. A mensagem é automaticamente apagada após o tempo determinado, começando a contagem a partir do momento da visualização da mesma |
| <h4><b>FA4 - Enviar áudio</b></h4> |
| Usuário 1 envia uma mensagem de áudio para o usuário 2 |
| <h4><b>FA5 - Escolher o ponto de início do áudio/ Dar play e pause no áudio</b></h4> |
| O usuário 2 pausa o áudio que havia recebido do usuário 1 e escolhe escutá-lo a partir dos últimos segundos. |
| <h4><b>FA6 - Editar mensagem</b></h4> |
| Usuário 1 envia uma mensagem de texto para o usuário 2 e depois edita o que estava escrito na mensagem |
| <h4><b>FA7 - Encaminhar mensagem</b></h4> |
| Usuário 1 encaminha uma mensagem que recebeu do usuário 2 para um terceiro usuário |
| <h4><b>FA8 - Enviar e abrir arquivos</b></h4> |
| Usuário 1 envia uma mensagem que possui um arquivo no formato PDF para o usuário 2, que o abre no próprio aplicativo após recebê-lo |
| <h4><b>FA9 - Enviar e editar imagem</b></h4> |
| Usuário 1 recorta uma imagem que achou na internet e a enviar para o usuário 2 |

### **UC14 - Fazer Backup de mensagens**
| |
| - |
| <h4><b>Fluxo Básico</b></h4> | 
| O usuário 1 faz o backup das conversas que possui no aplicativo, salvando-as no Desktop pessoal dele | 