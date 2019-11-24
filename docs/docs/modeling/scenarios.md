| Data | Versão | Descrição | Autor |
| --- | --- | --- | --- |
| 26/09/2019 | 1.0 | Criação do documento de Cenários | [Caio Fernandes](https://github.com/caiovfernandes) e [Gabriel Alves](https://github.com/gitgabiru)|
| 07/10/2019 | 1.1 | Melhoria do Layout |[Caio Fernandes](https://github.com/caiovfernandes) |
| 22/11/2019 | 2.0 | Refatoração dos cenários | Lucas Fellipe e Guilherme Mendes |



# Cenários - Modelagem de Requisitos
<p align="justify">
Trata-se de uma estratégia reconhecida para compreender as interações entre ambientes e sistemas,
assim como elicitara parte comportamental do software, sua dinãnima e/ou seu fluxo. 
</p>    

## **Tipos de Cenários *Wire* App:**

<button data-toggle="collapse" data-target="#config" class="myButton" >Configurações</button>
<div id="config" class="collapse">

[CC01](docs/modeling/scenarios?id=cenário-de-configuração-1)<br>
[CC02](docs/modeling/scenarios?id=cenário-de-configuração-2)<br>
[CC03](docs/modeling/scenarios?id=cenário-de-configuração-3)<br>
[CC04](docs/modeling/scenarios?id=cenário-de-configuração-4)<br>
[CC05](docs/modeling/scenarios?id=cenário-de-configuração-5)<br>
[CC06](docs/modeling/scenarios?id=cenário-de-configuração-6)<br>
[CC07](docs/modeling/scenarios?id=cenário-de-configuração-7)<br>
[CC08](docs/modeling/scenarios?id=cenário-de-configuração-8)<br>
[CC09](docs/modeling/scenarios?id=cenário-de-configuração-9)<br>
[CC10](docs/modeling/scenarios?id=cenário-de-configuração-10)<br>
[CC11](docs/modeling/scenarios?id=cenário-de-configuração-11)<br>
[CC12](docs/modeling/scenarios?id=cenário-de-configuração-12)<br>
[CC13](docs/modeling/scenarios?id=cenário-de-configuração-13)<br>
[CC14](docs/modeling/scenarios?id=cenário-de-configuração-14)<br>
[CC15](docs/modeling/scenarios?id=cenário-de-configuração-15)<br>
[CC16](docs/modeling/scenarios?id=cenário-de-configuração-16)<br>
[CC17](docs/modeling/scenarios?id=cenário-de-configuração-17)<br>
[CC18](docs/modeling/scenarios?id=cenário-de-configuração-18)<br>
[CC19](docs/modeling/scenarios?id=cenário-de-configuração-19)<br>
[CC20](docs/modeling/scenarios?id=cenário-de-configuração-20)<br>
</div>

<button data-toggle="collapse" data-target="#chat" class="myButton" >Chat</button>
<div id="chat" class="collapse">

[CM01](/docs/modeling/scenarios?id=cenário-de-chat-1)<br>
[CM02](/docs/modeling/scenarios?id=cenário-de-chat-2)<br>
[CM03](/docs/modeling/scenarios?id=cenário-de-chat-3)<br>
[CM04](/docs/modeling/scenarios?id=cenário-de-chat-4)<br>
[CM05](/docs/modeling/scenarios?id=cenário-de-chat-5)<br>
[CM06](/docs/modeling/scenarios?id=cenário-de-chat-6)<br>
[CM07](/docs/modeling/scenarios?id=cenário-de-chat-7)<br>
[CM08](/docs/modeling/scenarios?id=cenário-de-chat-8)<br>
[CM09](/docs/modeling/scenarios?id=cenário-de-chat-9)<br>
[CM10](/docs/modeling/scenarios?id=cenário-de-chat-10)<br>
[CM11](/docs/modeling/scenarios?id=cenário-de-chat-11)<br>
[CM12](/docs/modeling/scenarios?id=cenário-de-chat-12)<br>
[CM13](/docs/modeling/scenarios?id=cenário-de-chat-13)<br>
</div>

<button data-toggle="collapse" data-target="#equipes" class="myButton" >Equipes</button>
<div id="equipes" class="collapse">

[CE01](/docs/modeling/scenarios?id=cenário-de-equipe-01)<br>
[CE02](/docs/modeling/scenarios?id=cenário-de-equipe-02)<br>
[CE03](/docs/modeling/scenarios?id=cenário-de-equipe-03)<br>
[CE04](/docs/modeling/scenarios?id=cenário-de-equipe-04)<br>
[CE05](/docs/modeling/scenarios?id=cenário-de-equipe-05)<br>
[CE06](/docs/modeling/scenarios?id=cenário-de-equipe-06)<br>
</div>

<button data-toggle="collapse" data-target="#servicos" class="myButton" >Serviços</button>
<div id="servicos" class="collapse">

[CS01](/docs/modeling/scenarios?id=cenário-de-serviços-01)<br>
[CS02](/docs/modeling/scenarios?id=cenário-de-serviços-02)<br>
[CS03](/docs/modeling/scenarios?id=cenário-de-serviços-03)<br>
[CS04](/docs/modeling/scenarios?id=cenário-de-serviços-04)<br>
[CS05](/docs/modeling/scenarios?id=cenário-de-serviços-05)<br>
</div>

---

## **Configurações**
Cenários referentes as funcionalidades que provêm das configurações de serviço.

### Cenário de Configuração 1

|           |               |
|-----------|---------------|
| **Id**  | CC01 |
| **Título**  | Redefinir senha |
| **Metas e Objetivos**  | Trocar a senha atual e confirmar a alteração via e-mail. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O usuário deve possuir uma conta. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa conta <br> -  [Usuário](/docs/modeling/lexicos/objects?id=usuário) redefine a senha | 

<br>

### Cenário de Configuração 2
|           |               |
|-----------|---------------|
| **Id**  | CC02 |
| **Título**  |  Excluir conta |
| **Metas e Objetivos**  | Ter a conta excluida permanentemente do aplicativo. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | -  [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> -  [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa conta. <br> -  [Usuário](/docs/modeling/lexicos/objects?id=usuário) exclui sua conta permanentemente. |

<br>

### Cenário de Configuração 3
|           |               |
|-----------|---------------|
| **Id**  | CC03 |
| **Título**  | Dar permissão e utilizar dados móveis |
| **Metas e Objetivos**  | Enviar mensagens e dados anônimos aos [Usuário](/docs/modeling/lexicos/objects?id=usuário) e receber notícias do aplicativo. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | -  [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa conta. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita a opção de envio de dados anônimos e a opção de receber notícias. |

<br>

### Cenário de Configuração 4
|           |               |
|-----------|---------------|
| **Id**  | CC04 |
| **Título**  | Criar *backup* de uma conversa |
| **Metas e Objetivos**  | Criar um *backup* para preservar seu histórico de conversa. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa conta. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita a opção de fazer o *backup* de uma conversa. |

<br>

### Cenário de Configuração 5
|           |               |
|-----------|---------------|
| **Id**  | CC05 |
| **Título**  | Alterar nome pessoal |
| **Metas e Objetivos**  | Mudar seu nome pessoal. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa conta. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) altera seu nome pessoal conforme a sua vontade. |

<br>

### Cenário de Configuração 6
|           |               |
|-----------|---------------|
| **Id**  | CC06 |
| **Título**  | Alterar nome de [Usuário](/docs/modeling/lexicos/objects?id=usuário) |
| **Metas e Objetivos**  | Alteração do seu *username*. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa conta. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) altera seu *username* conforme a sua vontade e disponibilidade no aplicativo. |

<br>

### Cenário de Configuração 7
|           |               |
|-----------|---------------|
| **Id**  | CC07 |
| **Título**  | Adição de novo *e-mail* ao aplicativo |
| **Metas e Objetivos**  | Adição de um novo *e-mail* ao aplicativo. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa conta. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) adiciona um novo *e-mail* a sua conta. |

<br>

### Cenário de Configuração 8
|           |               |
|-----------|---------------|
| **Id**  | CC08 |
| **Título**  | Adição de novo número de telefone |
| **Metas e Objetivos**  | Adição de um novo número de telefone válido ao aplicativo. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa conta. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) adiciona um novo número de telefone válido a sua conta. |

<br>

### Cenário de Configuração 9
|           |               |
|-----------|---------------|
| **Id**  | CC09 |
| **Título**  | Adicionar nova imagem ao perfil de [Usuário](/docs/modeling/lexicos/objects?id=usuário) |
| **Metas e Objetivos**  | Adição de uma nova imagem ao perfil de [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa conta. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) adiciona uma nova foto de perfil. |

<br>

### Cenário de Configuração 10
|           |               |
|-----------|---------------|
| **Id**  | CC10 |
| **Título**  | Compartilhar contatos |
| **Metas e Objetivos**  | Compartilhar os contatos salvos no smartphone com o aplicativo para o [Usuário](/docs/modeling/lexicos/objects?id=usuário) encontre os seus contatos no *Wire* |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita a opção de compartilhar contatos. |

<br>

### Cenário de Configuração 11
|           |               |
|-----------|---------------|
| **Id**  | CC11 |
| **Título**  | Ativar modo vibração de notificação |
| **Metas e Objetivos**  | Habilitar o modo vibração para as notificações recebidas de um determinado [Usuário](/docs/modeling/lexicos/objects?id=usuário) ou grupo. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita a opção de modo vibração do aplicativo. |

<br>

### Cenário de Configuração 12
|           |               |
|-----------|---------------|
| **Id**  | CC12 |
| **Título** | Habilitar toque sonoro de notificação |
| **Metas/Objetivos** | Habilitar toque sonoro para todas as notificações recebidas. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita a opção de toque sonoro para as notificações. |

<br>

### Cenário de Configuração 13
|           |               |
|-----------|---------------|
| **Id**  | CC13 |
| **Título** |  Escolher toque sonoro de chamada |
| **Metas/Objetivos** | Escolher toque sonoro específico para as chamadas recebidas. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) escolhe o toque sonoro de chamadas desejado. |

<br>

### Cenário de Configuração 14
|           |               |
|-----------|---------------|
| **Id**  | CC14 |
| **Título** | Escolher toque sonoro de mensagem |
| **Metas/Objetivos** | Escolher toque sonoro específico para as mensagens recebidas. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) escolhe o toque sonoro de mensagens desejado. |

<br>
	       
### Cenário de Configuração 15
|           |               |
|-----------|---------------|
| **Id**  | CC15 |
| **Título:** | Escolher tema *dark*  |
| **Metas/Objetivos** | Habilitar modo *dark* no aplicativo. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita o modo *dark*. |

<br>

### Cenário de Configuração 16
|           |               |
|-----------|---------------|
| **Id**  | CC16 |
| **Título** | Esconder o conteúdo da tela do aplicativo |
| **Metas/Objetivos** | Habilitar esconder conteúdo da tela de tarefas. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita esconder o conteúdo da tela de tarefas. |

<br>

### Cenário de Configuração 17
|           |               |
|-----------|---------------|
| **Id**  | CC17 |
| **Título** | Pré-visualizar Mensagens |
| **Metas/Objetivos** | Habilitar pré-visualizar mensagens na tela de notificações. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita pré-visualizar mensagens. |

<br>

### Cenário de Configuração 18
|           |               |
|-----------|---------------|
| **Id**  | CC18 |
| **Título** | *Download* automático de imagens |
| **Metas/Objetivos** | Habilitar opção de *download* automático de imagens. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita a opção de *download* de imagens. |

<br>

### Cenário de Configuração 19
|           |               |
|-----------|---------------|
| **Id**  | CC19 |
| **Título** | Habilitar botão de envio no teclado |
| **Metas/Objetivos** | Habilitar botão de envio no teclado para enviar a mensagem de forma mais rápida. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita o botão de envio do teclado. |

<br>
   
### Cenário de Configuração 20
|           |               |
|-----------|---------------|
| **Id**  | CC20 |
| **Título** | Bloquear a tela por inatividade |
| **Metas/Objetivos** | Habilitar o bloqueio com senha após X segundos de inatividade no aplicativo. |
| **Contexto**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta e estar logado. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa opções. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilita a opção de bloqueio por inatividade. |

<br>
<br>

## **Chat**
Cenários da tela do chat do aplicativo *Wire*. Descreve de forma suscinta e clara as funcionalidades existentes na tela do chat de conversa.

### Cenário de Chat 1
|           |               |
|-----------|---------------|
| **Id**  | CM01 |
| **Título**  | Enviar ou receber mensagens de texto |
| **Metas e Objetivos** | Enviar ou receber mensagens de um determinado [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Contexto:**  | - Local: Tela de conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)**  |  Dois [Usuário](/docs/modeling/lexicos/objects?id=usuário) ou dois amigos. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1 abre conversa de um [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2. <br>  - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1 envia mensagem de texto para [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2 recebe mensagem de texto do [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1. |

<br>

### Cenário de Chat 2
|           |               |
|-----------|---------------|
| **Id**  | CM02 |
| **Título**  | Enviar ou receber mensagens de áudio |
| **Metas e Objetivos** | Enviar ou receber mensagens de áudio/voz de um determinado [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Contexto:**  | - Local: Tela de conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. Além disso, é necessário ativar a opção de habilitar envio de áudio. |
| **Ator(es)**  |  Dois [Usuário](/docs/modeling/lexicos/objects?id=usuário) ou dois amigos. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1 abre conversa de um [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2. <br>  - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1 envia mensagem de áudio/voz para [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2 recebe mensagem de áudio/voz do [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1. |

<br>

### Cenário de Chat 3
|           |               |
|-----------|---------------|
| **Id**  | CM03 |
| **Título**  | Enviar ou receber fotos e vídeos |
| **Metas e Objetivos** | Enviar ou receber fotos e/ou vídeos de um determinado [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Contexto:**  | - Local: Tela de conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)**  |  Dois [Usuário](/docs/modeling/lexicos/objects?id=usuário), dois amigos ou [Usuário](/docs/modeling/lexicos/objects?id=usuário) em uma equipe. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - O dono da equipe abre o grupo. <br> - O dono da equipe envia foto e/ou vídeo de um determinado projeto para a equipe. |

<br>

### Cenário de Chat 4
|           |               |
|-----------|---------------|
| **Id**  | CM04 |
| **Título**  | Criar um grupo |
| **Metas e Objetivos**  | Criar um grupo para adicionar várias pessoas para ter uma comunicação mais efetiva entre todos os membros do grupo. |
| **Contexto:**  | - Local: Tela de conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)** | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) procura opção de Criar grupo. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) adiciona os [Usuário](/docs/modeling/lexicos/objects?id=usuário) que vão pertencer à esse grupo. | 

<br>

### Cenário de Chat 5
|           |               |
|-----------|---------------|
| **Id**  | CM05 |
| **Título**  | Enviar mensagem com tempo de visualização |
| **Metas e Objetivos**  | Enviar uma mensagem que desapareça depois de um determinado tempo. |
| **Contexto:**  | - Local: Tela de conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)**  |  Dois [Usuário](/docs/modeling/lexicos/objects?id=usuário) ou dois amigos. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1 acessa a conversa com um determinado [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) seleciona a opção de enviar mensagem com tempo de visualização. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) determina o tempo de visualização da mensagem. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) envia mensagem. |

<br>

### Cenário de Chat 6
|           |               |
|-----------|---------------|
| **Id**  | CM06 |
| **Título**  | Chamar a atenção de um determinado [Usuário](/docs/modeling/lexicos/objects?id=usuário) |
| **Metas e Objetivos**  | Chamar a atenção de um determinado [Usuário](/docs/modeling/lexicos/objects?id=usuário) com um toque sonoro. |
| **Contexto:**  | - Local: Tela de conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)**  |  Dois [Usuário](/docs/modeling/lexicos/objects?id=usuário) ou dois amigos. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1 acessa conversa com um determinado [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1 aperta na opção de chamar a atenção. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2 recebe um toque sonoro. |

<br>

### Cenário de Chat 7
|           |               |
|-----------|---------------|
| **Id**  | CM07 |
| **Título**  | Enviar uma mensagem utilizando a formatação de texto *markdown* |
| **Metas e Objetivos**  | Enviar uma mensagem para um determinado [Usuário](/docs/modeling/lexicos/objects?id=usuário) utilizando a formatação *markdown* |
| **Contexto:**  | - Local: Tela de conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)**  |  Dois [Usuário](/docs/modeling/lexicos/objects?id=usuário) ou dois amigos. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) abre conversa com um [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1 envia mensagem no formato *markdown* para um [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2. |

<br>

### Cenário de Chat 8
|           |               |
|-----------|---------------|
| **Id**  | CM08 |
| **Título**  | Video-conferência em grupo. |
| **Metas e Objetivos**  | Realizar uma vídeo-conferência com a equipe. |
| **Contexto:** | - Local: Tela de conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)**  | Equipe, dois [Usuário](/docs/modeling/lexicos/objects?id=usuário) ou dois amigos. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - Dono da equipe abre a conversa. <br> - Dono da equipe realiza uma vídeo-conferência com todos os integrantes. |

<br>

### Cenário de Chat 9
|           |               |
|-----------|---------------|
| **Id**  | CM09 |
| **Título**  | Enviar ou receber um *GIF* na mensagem |
| **Metas e Objetivos**  | Enviar um *GIF* na mensagem para demonstrar alguma emoção. |
| **Contexto:**  | - Local: Tela de conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)**  | Dois [Usuário](/docs/modeling/lexicos/objects?id=usuário) ou dois amigos. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1 abre conversa com um [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1 envia um *GIF* animado para o [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) 2 recebe *GIF* animado do [Usuário](/docs/modeling/lexicos/objects?id=usuário) 1. |

<br>

### Cenário de Chat 10
|           |               |
|-----------|---------------|
| **Id**  | CM10 |
| **Título**  | Arquivar conversa |
| **Metas e Objetivos**  | Arquivar uma conversa. |
| **Contexto:**  | - Local: Tela de conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) abre conversa. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) arquiva conversa. |

<br>

### Cenário de Chat 11
|           |               |
|-----------|---------------|
| **Id**  | CM11 |
| **Título**  | Possuir múltiplas contas. |
| **Metas e Objetivos**  | Possuir mais de uma conta simultaneamente. |
| **Contexto:**  | - Local: Tela de ajustes. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:** | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa seu perfil. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa ajustes. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa conta. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa uma nova conta. |

<br>

### Cenário de Chat 12
|           |               |
|-----------|---------------|
| **Id**  | CM12 |
| **Título**  | Criar uma conversa para convidados que não estão no time |
| **Metas e Objetivos**  | Criar um chat para convidados que não fazem parte do time. |
| **Contexto:**  | - Local: Tela de inicial. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)**  | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa a opção de criar conversa. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) cria um "grupo" com todos os convidados. |

<br>

### Cenário de Chat 13
|           |               |
|-----------|---------------|
| **Id**  | CM13 |
| **Título**  | Reunião de planejamento |
| **Metas e Objetivos**  | Reunião para planejar os objetivos e metas de um projeto. |
| **Contexto:**  | - Local: Tela de inicial. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)** | [Usuário](/docs/modeling/lexicos/objects?id=usuário) de uma equipe. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:**  | - Dono da reunião manda mensagem de texto para os funcionários. <br> - Os funcionários respondem se estão de acordo com o planejamento ou não. |

<br>


## **Equipes**
Na utilização do aplicativo *Wire* é possível criar equipes. Esta é uma funcionalidade que ajuda na utilização da ferramenta por grupos em empresas ou mesmo uma empresa como um todo.

### Cenário de Equipe 01
|           |               |
|-----------|---------------|
| **Id**  | CE01 |
| **Título** | Criar uma Equipe |
| **Metas/Objetivos** | Criar, adicionar ou remover membros de uma equipe. |
| **Contexto:**  | - Local: Tela configurações da conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)** | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:** | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) cria uma equipe. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) adiciona membros à equipe. |

<br>

### Cenário de Equipe 02
|           |               |
|-----------|---------------|
| **Id**  | CE02 |
| **Título** | Renomear equipe |
| **Metas/Objetivos** | Renomear equipe devido a um erro de escrita. |
| **Contexto:**  | - Local: Tela de configurações da conversa. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)** | Administrador da equipe. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:** | - Administrador abre as configurações do chat da equipe. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) renomeia a equipe. |

<br>

### Cenário de Equipe 03
|           |               |
|-----------|---------------|
| **Id**  | CE03 |
| **Título** | Gerenciar equipe |
| **Metas/Objetivos** | Gerenciar de forma eficiente a equipe. |
| **Contexto:** | - Local: Tela de configurações da equipe. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)** | Administrador da equipe. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:** | - O administrador da equipe deseja ter uma visão geral do time, uma visão geral dos seus membros e suas respectivas posições dentro do time. |

<br>

### Cenário de Equipe 04
|           |               |
|-----------|---------------|
| **Id**  | CE04 |
| **Título** | Adicionar ou remover ícone/logo da equipe |
| **Metas/Objetivos** | Adicionar, remover ou editar o ícone/logo da equipe. |
| **Contexto:** | - Local: Tela de configurações da equipe. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)** | Administrador da equipe. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:** | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa configurações da equipe. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) adiciona, remove ou edita o ícone/logo da equipe. |

<br>

### Cenário de Equipe 05
|           |               |
|-----------|---------------|
| **Id**  | CE05 |
| **Título** |  Adicionar ou remover um [Usuário](/docs/modeling/lexicos/objects?id=usuário) da equipe |
| **Metas/Objetivos** | Adicionar ou remover um [Usuário](/docs/modeling/lexicos/objects?id=usuário) da equipe. |
| **Contexto:** | - Local: Tela de configurações da equipe. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)** | Administrador da equipe. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:** | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa tela de configurações da equipe. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) adiciona ou remove [Usuário](/docs/modeling/lexicos/objects?id=usuário) da equipe. |

<br>

### Cenário de Equipe 06
|           |               |
|-----------|---------------|
| **Id**  | CE06 |
| **Título** | Excluir a equipe |
| **Metas/Objetivos** | Excluir a equipe. |
| **Contexto:** | - Local: Tela de configurações da equipe. <br> - Tempo: Em qualquer momento. <br> - Pré-condição: O [Usuário](/docs/modeling/lexicos/objects?id=usuário) deve possuir uma conta, estar logado e possuir algum dispositivo que seja compatível com o aplicativo. |
| **Ator(es)** | Administrador da equipe. |
| **Recursos**  | Smartphone e acesso à internet. |
| **Exceção**  | O [Usuário](/docs/modeling/lexicos/objects?id=usuário) não possuir internet ou estar sem bateria. |
| **Episódios:** | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa configurações da equipe. <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) exclui a equipe. |

<br>
<br>

## **Serviços**
Na utilização da aplicação *Wire* é possível utilizar serviços externos, tanto serviços já existentes e disponibilizados pela comunidade quanto algum serviço que o próprio utilizador tenha implementado para uso privado. Esta é uma funcionalidade que ajuda na utilização da ferramenta por grupos, empresas ou mesmo um [Usuário](/docs/modeling/lexicos/objects?id=usuário) convencional.


### Cenário de Serviços 01
|           |               |
|-----------|---------------|
| **Id**  | CS01 |
| **Título** | Acoplar serviço externo. |
| **Metas/Objetivos** | Trazer para o ambiente/conversas serviços externos ao *Wire*, pode ser utilizado um serviço existente ou também pode ser implementado um |novo serviço.
| **Contexto** | Perfil -> Serviços. |
| **Ator(es)** | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos** | SO compatível, internet e energia. |
| **Exeção** | Sem sinal, sem internet, serviço fora do ar.|
| **Episódos:** | - [Usuário](/docs/modeling/lexicos/objects?id=usuário) acopla um novo serviço |

<br>

### Cenário de Serviços 02
|           |               |
|-----------|---------------|
| **Id**  | CS02 |
| **Título** | Habilitar serviço. |
| **Metas/Objetivos** | Permitir ao [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilitar ou desabilitar um serviço acoplado.|
| **Contexto** | Perfil -> Serviços ou teams.*Wire*.com|
| **Ator(es)**|  [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos:** |O compatível, internet e energia. |
| **Exeção** | Sem sinal, sem internet, serviço fora do ar. |
| **Episódos** |	- [Usuário](/docs/modeling/lexicos/objects?id=usuário) acopla um novo serviço <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) ativa o serviço <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) desativa o serviço

<br>
	


### Cenário de Serviços 03
|           |               |
|-----------|---------------|
| **Id**  | CS03 |
| **Título** | Habilitar serviço. |
| **Metas/Objetivos** | Permitir ao [Usuário](/docs/modeling/lexicos/objects?id=usuário) habilitar ou desabilitar um serviço acoplado.|
| **Contexto** | Perfil -> Serviços ou teams.*Wire*.com|
| **Ator(es)** | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos** |O compatível, internet e energia. |
| **Exeção** | Sem sinal, sem internet, serviço fora do ar. |
| **Episódos** |	- [Usuário](/docs/modeling/lexicos/objects?id=usuário) acopla um novo serviço <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) ativa o serviço <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) desativa o serviço |

<br>


### Cenário de Serviços 04
|           |               |
|-----------|---------------|
| **Id**  | CS04|
| **Título** | Habilitar serviço para um grupo. |
| **Metas/Objetivos** | Permitir ao [Usuário](/docs/modeling/lexicos/objects?id=usuário) acoplar um serviço a uma conversa em grupo.|
| **Contexto** | Perfil -> Serviços ou teams.*Wire*.com| 
| **Ator(es)** | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos** |O compatível, internet e energia. |
| **Exeção** | Sem sinal, sem internet, serviço fora do ar. |
| **Episódos** |	- [Usuário](/docs/modeling/lexicos/objects?id=usuário) acopla um novo serviço<br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) ativa o serviço<br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) adiciona serviço ao grupo.|

<br>




### Cenário de Serviços 05
|           |               |
|-----------|---------------|
| **Id**  | CS05 |
| **Título** | Obter serviços. |
| **Metas/Objetivos** | Disponibilizar ao [Usuário](/docs/modeling/lexicos/objects?id=usuário) uma lista de serviços disponibilizados pela comunidade que ele possa usar.|
| **Contexto** | Perfil -> Serviços ou teams.*Wire*.com|  
| **Ator(es)** | [Usuário](/docs/modeling/lexicos/objects?id=usuário). |
| **Recursos:** |O compatível, internet e energia. |
| **Exeção** | Sem sinal, sem internet, serviço fora do ar. |
| **Episódos** |	- [Usuário](/docs/modeling/lexicos/objects?id=usuário) acessa a tela de serviços <br> - [Usuário](/docs/modeling/lexicos/objects?id=usuário) entra em gerenciar serviços.|

<br>



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

