# Objetos

| Data | Versão | Descrição | Autor |
| --- | --- | --- | --- |
| 30/09/2019 | 1.0 | Criação dos léxicos - Objetos  | João Pedro e Lucas Fellipe |
| 24/11/2019 | 2.0 | Correção dos léxicos - Objetos  | Gabriel Alves |

## Administrador
|           |               |
|-----------|---------------|
| **Nome**  |Administrador|
| **Classificação** | Objeto |
| **Sinônimos** | Admin, adm|
| **Noção**     |Usuário com permissões em um [grupo](/docs/modeling/lexicos/objects?id=grupo)| 
| **Impacto**   |[Adicionar usuário no grupo](/docs/modeling/lexicos/verbs?id=adicionar-usuários-no-grupo)<br>[Remover usuário do grupo](/docs/modeling/lexicos/verbs?id=remover-usuários-do-grupo)<br>[Definir cargo às pessoas](/docs/modeling/lexicos/verbs?id=definir-permissões-de-cada-usuário)<br>[Enviar mensagem](/docs/modeling/lexicos/verbs?id=enviar-mensagem)|

## Arquivo
|           |               |
|-----------|---------------|
| **Nome**  |Arquivo|
| **Classificação** | Objeto |
| **Sinônimos** | registro, ficha |
| **Noção**     |Documento que pode ser do tipo [áudio](/docs/modeling/lexicos/objects?id=Áudio), [imagem](/docs/modeling/lexicos/objects?id=imagem), [vídeo](/docs/modeling/lexicos/objects?id=vídeo), [texto](/docs/modeling/lexicos/objects?id=texto) entre outros | 
| **Impacto**   | [Enviar arquivo](/docs/modeling/lexicos/verbs?id=enviar-arquivo)<br>[Baixar arquivo](/docs/modeling/lexicos/verbs?id=baixar-arquivo)<br>[Enviar mensagem](/docs/modeling/lexicos/verbs?id=enviar-mensagem)|

## Áudio
|           |               |
|-----------|---------------|
| **Nome**  |   Áudio    |
| **Classificação** | Objeto |
| **Sinônimos** | Mensagem de voz|
| **Noção**     | Forma de comunicação através da reprodução de sons|
| **Impacto**   | [Enviar mensagem](/docs/modeling/lexicos/verbs?id=enviar-mensagem)<br>[Selecionar Mensagem](/docs/modeling/lexicos/verbs?id=selecionar-mensagem)<br>[Definir quanto tempo a mensagem fica visivel](/docs/modeling/lexicos/verbs?id=definir-quanto-tempo-a-mensagem-fica-visivel)<br>[Apagar Mensagem](/docs/modeling/lexicos/verbs?id=apagar-mensagem)<br>[Encaminhar mensagem](/docs/modeling/lexicos/verbs?id=encaminhar-mensagem)<br> [Executar áudio](/docs/modeling/lexicos/verbs?id=executar-áudio)<br>[Pausar áudio](/docs/modeling/lexicos/verbs?id=parar-a-execução-do-áudio)<br>[Navegar por qualquer ponto do áudio](/docs/modeling/lexicos/verbs?id=navegar-por-qualquer-ponto-do-áudio)<br>[Enviar mensagem](/docs/modeling/lexicos/verbs?id=enviar-mensagem)|


## Câmera
|           |               |
|-----------|---------------|
| **Nome**  |Câmera|
| **Classificação** | Objeto |
| **Sinônimos** | filmadora |
| **Noção**     | O objeto é utilizado para [enviar foto ou vídeo](/docs/modeling/lexicos/verbs?id=enviar-foto-ou-vídeo) e realizar [chamada de vídeo](/docs/modeling/lexicos/verbs?id=chamada-de-vídeo)| 
| **Impacto**   |[Ligar câmera](/docs/modeling/lexicos/verbs?id=ligar-câmera)<br>[Desligar câmera](/docs/modeling/lexicos/verbs?id=desligar-câmera)<br> [Fazer chamada](/docs/modeling/lexicos/verbs?id=fazer-chamada)<br>[Enviar foto ou vídeo](/docs/modeling/lexicos/verbs?id=enviar-foto-ou-vídeo)<br>[Enviar mensagem](/docs/modeling/lexicos/verbs?id=enviar-mensagem)|

## Chamada
|           |               |
|-----------|---------------|
| **Nome**  |   Chamada    |
| **Classificação** | Objeto |
| **Sinônimos** | Ligação|
| **Noção**     | Forma de comunicação entre duas ou mais pessoas, podendo ser [chamada de voz](#Chamada-de-voz) ou [chamada de vídeo](#Chamada-de-vídeo)|
| **Impacto**   | [Fazer chamada](/docs/modeling/lexicos/verbs?id=fazer-chamada)<br>[Adicionar pessoas a chamada](/docs/modeling/lexicos/verbs?id=adicionar-pessoas-a-chamada)<br>[Entrar em chamada já existente](/docs/modeling/lexicos/verbs?id=entrar-em-chamada-já-existente)<br>[Mutar o microfone](/docs/modeling/lexicos/verbs?id=silenciar-microfone)<br>[Ligar o microfone](/docs/modeling/lexicos/verbs?id=ligar-microfone)<br>[Ligar câmera](/docs/modeling/lexicos/verbs?id=ligar-câmera)<br>[Desligar câmera](/docs/modeling/lexicos/verbs?id=desligar-câmera)<br>[Sair da chamada](/docs/modeling/lexicos/verbs?id=sair-da-chamada)|

## Chamada de vídeo
|           |               |
|-----------|---------------|
| **Nome**  |   Chamada de vídeo|
| **Classificação** | Objeto |
| **Sinônimos** | Videochamada|
| **Noção**     | Forma de comunicação entre duas ou mais pessoas de forma audiovisual, podendo ser utilizada a [câmera]()
| **Impacto**   | [Fazer chamada](/docs/modeling/lexicos/verbs?id=fazer-chamada)<br>[Adicionar pessoas a chamada](/docs/modeling/lexicos/verbs?id=adicionar-pessoas-a-chamada)<br>[Entrar em chamada já existente](/docs/modeling/lexicos/verbs?id=entrar-em-chamada-já-existente)<br>[Mutar o microfone](/docs/modeling/lexicos/verbs?id=silenciar-microfone)<br>[Ligar o microfone](/docs/modeling/lexicos/verbs?id=ligar-microfone)<br>[Ligar câmera](/docs/modeling/lexicos/verbs?id=ligar-câmera)<br>[Desligar câmera](/docs/modeling/lexicos/verbs?id=desligar-câmera)<br>[Sair da chamada](/docs/modeling/lexicos/verbs?id=sair-da-chamada)|

## Chamada de voz
|           |               |
|-----------|---------------|
| **Nome**  |   Chamada de voz|
| **Classificação** | Objeto |
| **Sinônimos** | Ligação|
| **Noção**     | Forma de comunicação entre duas ou mais pessoas de forma auditiva, utilizando apenas o [microfone](microfone)
| **Impacto**   | [Fazer chamada](/docs/modeling/lexicos/verbs?id=fazer-chamada)<br>[Adicionar pessoas a chamada](/docs/modeling/lexicos/verbs?id=adicionar-pessoas-a-chamada)<br>[Entrar em chamada já existente](/docs/modeling/lexicos/verbs?id=entrar-em-chamada-já-existente)<br>[Mutar o microfone](/docs/modeling/lexicos/verbs?id=silenciar-microfone)<br>[Ligar o microfone](/docs/modeling/lexicos/verbs?id=ligar-microfone)<br>[Sair da chamada](/docs/modeling/lexicos/verbs?id=sair-da-chamada)|

## Conta de usuário
|           |               |
|-----------|---------------|
| **Nome**  |Conta de usuário|
| **Classificação** | Objeto |
| **Sinônimos** |Conta|
| **Noção**     |Onde ficam todos os dados do usuário, criada após o [cadastrar]()| 
| **Impacto**   | [Criar conta pelo e-mail](/docs/modeling/lexicos/verbs?id=cadastrar-usuário-pelo-e-mail)<br>[Criar conta pelo número](/docs/modeling/lexicos/verbs?id=cadastrar-usuário-pelo-número)<br>[Deletar conta]()|

## Contato
|           |               |
|-----------|---------------|
| **Nome**  |Contato|
| **Classificação** | Objeto |
| **Sinônimos** | amigo(a) |
| **Noção**     |Quando você adiciona outro usuário na sua lista de contatos e a partir disso é capaz de conversar com ele| 
| **Impacto**   |[Adicionar contatos](/docs/modeling/lexicos/verbs?id=adicionar-contatos)<br>[Editar dados do contato](/docs/modeling/lexicos/verbs?id=editar-dados-do-contato)|

## Grupo
|           |               |
|-----------|---------------|
| **Nome**  |Grupo|
| **Classificação** | Objeto |
| **Sinônimos** | povo |
| **Noção**     |Canal de comunicação formado por 2 ou mais [usuários](/docs/modeling/lexicos/objects?id=usuário)| 
| **Impacto**   |Troca de conteúdo entre vários membros|

## Imagem

|           |               |
|-----------|---------------|
| **Nome**  |   Imagem      |
| **Classificação** | Objeto |
| **Sinônimos** | Foto |
| **Noção**     | Forma de comunicação visual|
| **Impacto**   | [Enviar mensagem](/docs/modeling/lexicos/verbs?id=enviar-mensagem)<br>[Editar de imagem](/docs/modeling/lexicos/verbs?id=editar-foto)<br>[Selecionar Mensagem](/docs/modeling/lexicos/verbs?id=selecionar-mensagem)<br>[Definir quanto tempo a mensagem fica visivel](/docs/modeling/lexicos/verbs?id=definir-quanto-tempo-a-mensagem-fica-visivel)<br>[Apagar Mensagem](/docs/modeling/lexicos/verbs?id=apagar-mensagem)<br>[Encaminhar mensagem](/docs/modeling/lexicos/verbs?id=encaminhar-mensagem)|

## Lista de contatos
|           |               |
|-----------|---------------|
| **Nome**  |Lista de contatos|
| **Classificação** | Objeto |
| **Sinônimos** | agenda |
| **Noção**     |Lista onde ficam armazenados todos os seus [contatos](/docs/modeling/lexicos/objects?id=contato)| 
| **Impacto**   |[Adicionar contatos](/docs/modeling/lexicos/verbs?id=adicionar-contatos)<br>[Editar dados do contato](/docs/modeling/lexicos/verbs?id=editar-dados-do-contato)|







## Mensagem

|           |               |
|-----------|---------------|
| **Nome**  |   Mensagem    |
| **Classificação** | Objeto |
| **Sinônimos** | comunicado |
| **Noção**     | Forma de comunicação, podendo ser por via de [áudio](#áudio), [imagem](#imagem), [texto](#texto) ou [vídeo](#vídeo)|
| **Impacto**   | [Enviar mensagem](/docs/modeling/lexicos/verbs?id=enviar-mensagem)<br>[Editar de mensagem](/docs/modeling/lexicos/verbs?id=editar-mensagem)<br>[Selecionar Mensagem](/docs/modeling/lexicos/verbs?id=selecionar-mensagem)<br>[Definir quanto tempo a mensagem fica visivel](/docs/modeling/lexicos/verbs?id=definir-quanto-tempo-a-mensagem-fica-visivel)<br>[Apagar Mensagem](/docs/modeling/lexicos/verbs?id=apagar-mensagem)<br>[Encaminhar mensagem](/docs/modeling/lexicos/verbs?id=encaminhar-mensagem)|

## Microfone
|           |               |
|-----------|---------------|
| **Nome**  |Microfone|
| **Classificação** | Objeto |
| **Sinônimos** | gravador |
| **Noção**     | O objeto é utilizado para comunicação sonora de [chamada de voz](/docs/modeling/lexicos/verbs?id=chamada-de-voz) e [chamada de vídeo](/docs/modeling/lexicos/verbs?id=chamada-de-vídeo)| 
| **Impacto**   | [Ligar o microfone](/docs/modeling/lexicos/verbs?id=ligar-microfone)<br>[Desligar microfone](/docs/modeling/lexicos/verbs?id=desligar-microfone)<br>[Fazer chamada](/docs/modeling/lexicos/verbs?id=fazer-chamada)<br>[Enviar áudio](/docs/modeling/lexicos/verbs?id=enviar-áudio)<br>[Enviar mensagem](/docs/modeling/lexicos/verbs?id=enviar-mensagem)|

## Nome de usuário
|           |               |
|-----------|---------------|
| **Nome**  |Nome de usuário|
| **Classificação** | Objeto |
| **Sinônimos** | Nickname, username, user|
| **Noção**     |Nome pelo qual o usuário pode ser referenciado| 
| **Impacto**   |[Referenciar por nome de usuário](/docs/modeling/lexicos/verbs?id=referenciar-pelo-nome-de-usuário)<br>[Adicionar pessoas](/docs/modeling/lexicos/verbs?id=adicionar-contatos)|

## Perfil
|           |               |
|-----------|---------------|
| **Nome**  |Perfil|
| **Classificação** | Objeto |
| **Sinônimos** | descrição |
| **Noção**     |Local onde as informações sobre o [usuário](/docs/modeling/lexicos/objects?id=usuário) ficam armazenadas| 
| **Impacto**   |[Editar Perfil](/docs/modeling/lexicos/verbs?id=editar-perfil)|


## Texto
|           |               |
|-----------|---------------|
| **Nome**  |   Texto    |
| **Classificação** | Objeto |
| **Sinônimos** | Mensagem de texto|
| **Noção**     | Forma de comunicação escrita|
| **Impacto**   | [Enviar mensagem](/docs/modeling/lexicos/verbs?id=enviar-mensagem)<br>[Editar de mensagem](/docs/modeling/lexicos/verbs?id=editar-mensagem)<br>[Selecionar Mensagem](/docs/modeling/lexicos/verbs?id=selecionar-mensagem)<br>[Definir quanto tempo a mensagem fica visivel](/docs/modeling/lexicos/verbs?id=definir-quanto-tempo-a-mensagem-fica-visivel)<br>[Apagar Mensagem](/docs/modeling/lexicos/verbs?id=apagar-mensagem)<br>[Encaminhar mensagem](/docs/modeling/lexicos/verbs?id=encaminhar-mensagem)|

## Usuário
|           |               |
|-----------|---------------|
| **Nome**  |Usuário|
| **Classificação** | Objeto |
| **Sinônimos** | cliente |
| **Noção**     |Pessoa que utiliza a aplicação e possui uma [conta de usuário](#conta-de-usuário)| 
| **Impacto**   | Tem acesso a todas as funcionalidades do aplicativo|

## Vídeo
|           |               |
|-----------|---------------|
| **Nome**  |   Vídeo    |
| **Classificação** | Objeto |
| **Sinônimos** | videoclipe |
| **Noção**     | Forma de comunicação audiovisual|
| **Impacto**   | [Enviar mensagem](/docs/modeling/lexicos/verbs?id=enviar-mensagem)<br>[Selecionar Mensagem](/docs/modeling/lexicos/verbs?id=selecionar-mensagem)<br>[Definir quanto tempo a mensagem fica visivel](/docs/modeling/lexicos/verbs?id=definir-quanto-tempo-a-mensagem-fica-visivel)<br>[Apagar Mensagem](/docs/modeling/lexicos/verbs?id=apagar-mensagem)<br>[Encaminhar mensagem](/docs/modeling/lexicos/verbs?id=encaminhar-mensagem)|

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