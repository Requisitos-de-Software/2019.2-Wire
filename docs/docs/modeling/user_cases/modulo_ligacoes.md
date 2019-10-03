# Módulo de Ligações

## Diagrama de casos de uso

![User Cases Diagram - Wire (Ligacoes)](https://user-images.githubusercontent.com/42645264/66132038-d323bd00-e5ca-11e9-82ab-722b13f2dc8c.png)

## Especificações dos casos de uso

|Casos de Uso|Ator|Descrição|
|---|---|------|
|UC15 - Fazer ligação| Usuário | Esse caso de uso permite o usuário se comunicar por meios além da mensagem|
|UC16 - Ligação de áudio| Usuário | Esse caso permite ao usuário a opção de ter uma conversa por áudio com outro usuário|
|UC17 - Ligar e desligar microfone| Usuário | Esse caso possibilita o usuário ligar e desligar o microfone, para que ele seja, ou não, escutado durante a ligação|
|UC18 - Entrar em ligação já existente| Usuário | Este caso de uso permite o usuário entrar em uma ligação, de áudio ou de vídeo, que está em execução|
|UC19 - Ligação de vídeo| Usuário | Esse caso de uso fornece ao usuário a opção de ter uma conversa por vídeo com outro usuário|
|UC20 - Ligar e desligar câmera| Usuário | Esse caso possibilita o usuário ligar e desligar a câmera de vídeo, para que ele seja, ou não, visto durante a ligação|
|UC21 - Adicionar pessoas à ligação| Usuário | Este caso de uso ocorre quando o usuário adiciona uma terceira pessoas à chamada atual, seja de áudio ou de vídeo|

## Fluxo de Eventos

### **UC15 - Fazer ligação**
| |
| - |
| <h3> Fluxo Básico </h3> |
| Usuário 1 liga, por áudio, para o usuário 2 |
| <h3> Fluxos Alternativos </h3> |
| <h4><b>  FA1 - Ligar e desligar microfone </b></h4> |
| Durante a ligação de áudio, o usuário 1 desliga seu microfone para que os ruídos vindos do ambiente em que ele está não atrapalhe a reunião |
| <h4><b>  FA2 - Entrar em ligação já existente </b></h4> |
| O usuário 3 se atrasa para uma reunião e, após chegar em um local com internet, entra na chamada que já estava sendo feita pelos outros usuários da reunião |
| <h4><b>  FA3 - Fazer ligação de vídeo </b></h4> |
| Usuário 1 liga, por vídeo, para o usuário 2 |
| <h4><b>  FA4 - Ligar e desligar câmera </b></h4> |
| Durante a ligação de vídeo, o usuário 1 desliga sua câmera para que possa digitar a senha de um cofre que está atrás dele |
| <h4><b>  FA5 - Adicionar pessoas à chamada </b></h4> |
| O usuário 1 inicia uma ligação de vídeo com o usuário 2 e adiciona o usuário 3, para que todos possam se comunicar diretamente |