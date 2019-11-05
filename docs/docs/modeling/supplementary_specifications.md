# Especificação Suplementar

| Data | Versão | Descrição | Autor |
| --- | --- | --- | --- |
| 26/09/2019 | 1.0 | Especificação Suplementar | Guilherme Mendes |

## Introdução
Uma especificação suplementar lista os requisitos não-funcionais do sistema, junto com as outras técnicas de modelagem e elicitação utilizadas é possível capturar o conjunto completo de requisitos do sistema.
### Finalidade
A especificação suplementar tem como finalidade definir os requisitos não funcionais do aplicativo Wire que não foram explicitados nas outras técnicas de modelagem de requisitos.
### Escopo
O Wire é uma solução de colaboração baseada na nuvem que oferece funcionalidades de chamadas em conferência, videoconferências, compartilhamento de tela e compartilhamento de arquivos em um conjunto.

## Descrição dos Requisitos não Funcionais
| ID | Descrição |
| --- | --- |
| RNF1 | Criptografia de ponta-a-ponta |
| RNF2 | Cadastro, configuração e utilização de até 8 contas simultâneas |
| RNF3 | Disponível em multiplataformas (independentes) |
| RNF4 | Customização de interface (foto de fundo, fonte, modo noturno) | 
| RNF5 | Proteção dos dados do usuário |
| RNF6 | Self-hosted e cloud manager |
| RNF7 | Multi Linguagem |
| RNF8 | Possibilidade de acoplar serviços externos |
| RNF9 | Compatibilidade com outros formatos de mensagem (markdown, GIFS, etc) |
| RNF10 | Check de visualização |
| RNF11 | Visto por último |
| RNF12 | Mensagem não enviada |

* [Imagem da lista de Requisitos Não Funcionais definidos pelo grupo.](https://user-images.githubusercontent.com/37874689/65926027-90df5d80-e3c9-11e9-8fdd-5339b99ecaf3.png)

### Referências
* https://docplayer.com.br/3800759-Php-software-company-samily-rocha-gois-francisco-luiz-sobrinho-projeto-de-software-floricultura-beija-flor-especificacao-suplementar-versao-101.html, acessado em 25 de Setembro
* https://wire.com/en/security/, acessado em 26 de Setembro
* https://requisitos-habitica.netlify.com/EspecificacaoSuplementar, acessado em 29 de Setembro

### Definições, Acrônimos e Abreviações
Disponível nos [Léxicos](/docs/modeling/lexicons).

### Visão Geral
Este documento apresenta, inicialmente, uma introdução ao Wire a fim de deixar claro o escopo do projeto. A seguir, são expostos os requisitos suplementares distribuídos em funcionalidade, usabilidade, confiabilidade, desempenho, suportabilidade e requisitos de licenciamento.

## Funcionalidades
As funcionalidades já elicitadas podem ser encontradas por toda a [Documentação](/docs/elicitation/elicitation) feita pelo grupo e nos [Casos de Uso](/docs/modeling/user_cases).

## Usabilidade
#### **Interface simples, minimalista e de fácil entendimento:**

A interface gráfica do Wire deve ser de fácil usabilidade, simples e minimalista, sendo intuitiva e sem complexidade de comandos, reduzindo ao máximo o tempo necessário para realizar qualquer atividade dentro da aplicação.

#### **Padrões visuais de interface:**
A interface deve utilizar padrões visuais de informação com cores e ícones intuitivos que ajude na identificação de itens e de funcionalidades.

#### **Conhecimento prévio do usuário:**
Será necessário na utilização da aplicação, que o usuário tenha um certo conhecimento prévio de tecnologias móveis (Android, iOS) e/ou sistemas Linux/Windows. No [Questionário](/docs/elicitation/forms) aponta que o público alvo já possui conhecimento essas tecnológias e utilizam aplicações semelhantes.

#### **Feedback:**
O Wire deve oferecer feedbacks instantânea ao usuário, de forma que ele entenda todo o processo de suas ações na aplicação, com respostas fluídas e rápidas.

## Confiabilidade
#### **Segurança dos dados:**
É garantido total segurança e privacidade no armazenamento do dados, mantendo os mesmos íntegros e protegido com criptografia de ponta a ponta seguindo as leis de privacidade.

#### **Disponibilidade:**
Os servidores do aplicativo devem mantê-lo disponível o maior tempo possível em todas as plataformas. Se houver indisponibilidade por motivos de manutenção ou atualização, o usuário deve ser previamente avisado.

#### **Suporte a falhas:**
A aplicação deve dar segurança ao usuário de que a falha vai ser corrigida e não haverá consequências negativas aos dados armazenados pelo usuário. Disponibilizando suporte para reportar erros.

## Desempenho

#### **Tempo mínimo de reposta:**
O aplicativo deve oferecer rapidez e fluidez nas respostas e redenrizações das atividades executadas pelo usuário. Envio e recebimento de mensagens deve ocorrer instantaneamente.
Conexões rápidas para chamadas de áudio e vídeo.

#### **Acessos simultâneos:**
A aplicação deve ser capaz de atender acessos simultâneos de diferentes usuários, sem causar nenhum prejuízo.

#### **Armazenamento:**
O Wire necessita de 21MB de armazemento no Android e 114,9 MB no iOS.


## Suportabilidade
A aplicação está disponível em todas as plataformas: Windows, MacOS, Linux, Android (5.0 ou superior
), iOS(iOS 10.0 ou superior) e Navegadores. 
Rastreabilidade com o público alvo: [Questionário](/docs/elicitation/forms?id=questão-11).

## Requisitos de Licenciamento
#### **Política de Privacidade**
A aplicação apresenta sua política de privacidade para que o usuário concorde em utilizar o aplicativo e suas informações dentro dos limites apresentados, com seguraça criptografada.
* Compatível com o GDPR;
* Código fonte Licença GPLv3;
* Kudelski Security e X41 D-Sec.


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