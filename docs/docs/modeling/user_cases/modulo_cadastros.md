# Módulo de Cadastros

## Diagrama de casos de uso

<img src="docs/assets/img/modeling/uc_diagrams/UserCasesDiagram_Wire_Cadastros.png">

<p align="right">
<a href="https://user-images.githubusercontent.com/42645264/66132055-dae36180-e5ca-11e9-9f44-bc78eb52e6b0.png"> Clique aqui para visualizar a imagem ampliada.
</p>


## Especificações dos casos de uso

|Casos de Uso|Ator|Descrição|
|---|---|------|
|UC32 - Fazer cadastro| Usuário | Esse caso de uso ocorre quando o usuário começa a usar o aplicativo e se cadastra pela primeira vez no mesmo, criando uma conta. É possível ter mais de uma conta|
|UC33 - Fazer cadastro pelo número de telefone| Usuário | Esse caso de uso fornece ao usuário a opção se cadastrar a partir do número de telefone utilizado|
|UC34 - Fazer cadastro pelo endereço de e-mail| Usuário | Esse caso de uso fornece ao usuário a opção se cadastrar a partir de um endereço de e-mail|
|UC35 - Definir nome de usuário| Usuário | Esse caso de uso permite o usuário definir o nome pelo qual será chamado dentro do aplicativo|
|UC36 - Criar um time| Usuário | Esse caso de uso possibilita ao usuário criar um time, ou seja, definir um grupo de usuário que tem mais contato com ele|
|UC37 - Criar um time| Usuário | Esse caso de uso permite o usuário adicionar pessoas ao time o qual ele pertence|

## Fluxo de Eventos

### **UC32 - Fazer cadastro**
| |
| - |
| <h3> Fluxo Básico </h3> |
| Usuário 1 entra no aplicativo pela primeira vez e faz seu cadastro a partir do número de telefone utilizado e em seguida define o nome de usuário pelo qual será chamado |
| <h3> Fluxos Alternativos </h3> |
| <h4><b> FA1 - Fazer cadastro pelo e-mail </b></h4> |
| Usuário 1 entra no aplicativo pela primeira vez e faz seu cadastro a partir de um endereço de e-mail |
| <h4><b> FA2 - Criar time e adicionar usuários ao time </b></h4> |
| Usuário 1, após definir o nome de usuário, cria um time para sua empresa e adiciona os funcionários que já estão cadastrados no aplicativo |