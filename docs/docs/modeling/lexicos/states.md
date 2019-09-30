# Estados
---

## **Mensagem**

|           |               |
|-----------|---------------|
| **Nome**  |   [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) enviada    |
| **Classificação** | Estado |
| **Sinônimos** | [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) entregue <br> [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) despachada|
| **Noção**     | A [mensagem](/docs/modeling/lexicos/objects?id=mensagem) foi enviada ao [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> Ocorre quando o [usuário](/docs/modeling/lexicos/objects?id=usuário) aperta no botão de enviar [mensagem](/docs/modeling/lexicos/objects?id=mensagem) |
| **Impacto**   | A [mensagem](/docs/modeling/lexicos/objects?id=mensagem) foi recebida pelo [usuário](/docs/modeling/lexicos/objects?id=usuário) |

### Mensagem apagada
|           |               |
|-----------|---------------|
| **Nome**  |   [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) apagada    |
| **Classificação** | Estado |
| **Sinônimos** | [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) deletada <br> [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) excluída |
| **Noção**     | A [mensagem](/docs/modeling/lexicos/objects?id=mensagem) foi deletada <br> Ocorre quando o [usuário](/docs/modeling/lexicos/objects?id=usuário) clica no botão de deletar [mensagem](/docs/modeling/lexicos/objects?id=mensagem) |
| **Impacto**   | O [usuário](/docs/modeling/lexicos/objects?id=usuário) não poderá mais ver a [mensagem](/docs/modeling/lexicos/objects?id=mensagem), devido ao fato que ela foi excluída |

### Visibilidade da mensagem por um determinado tempo
|           |               |
|-----------|---------------|
| **Nome**  | Visibilidade da [mensagem](/docs/modeling/lexicos/objects?id=mensagem) por um determinado tempo |
| **Classificação** | Estado |
| **Sinônimos** |  |
| **Noção**     | Quanto tempo a [mensagem](/docs/modeling/lexicos/objects?id=mensagem) ficará visível ao [usuário](/docs/modeling/lexicos/objects?id=usuário) |
| **Impacto**   | Visualização da [mensagem](/docs/modeling/lexicos/objects?id=mensagem) por um determinado tempo |

### Mensagem encaminhada
|           |               |
|-----------|---------------|
| **Nome**  |   [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) encaminhada    |
| **Classificação** | Estado |
| **Sinônimos** |  |
| **Noção**     | A [mensagem](/docs/modeling/lexicos/objects?id=mensagem) foi encaminhada ao [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> Ocorre quando o [usuário](/docs/modeling/lexicos/objects?id=usuário) aperta no botão de encaminhar [mensagem](/docs/modeling/lexicos/objects?id=mensagem) |
| **Impacto**   | [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) entregue ao destinatário <br> A [mensagem](/docs/modeling/lexicos/objects?id=mensagem) foi recebida pelo [usuário](/docs/modeling/lexicos/objects?id=usuário) |


### Mensagem respondida
|           |               |
|-----------|---------------|
| **Nome**  |   [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) respondida    |
| **Classificação** | Estado |
| **Sinônimos** | [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) refutada <br> [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) rebatida |
| **Noção**     | A [mensagem](/docs/modeling/lexicos/objects?id=mensagem) foi respondida <br> Ocorre quando o [usuário](/docs/modeling/lexicos/objects?id=usuário) recebe uma [mensagem](/docs/modeling/lexicos/objects?id=mensagem) e logo em seguida ele responde essa mesma [mensagem](/docs/modeling/lexicos/objects?id=mensagem) |
| **Impacto**   | A [mensagem](/docs/modeling/lexicos/objects?id=mensagem) enviada pelo [usuário](/docs/modeling/lexicos/objects?id=usuário) foi respondida por outro [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> O [usuário](/docs/modeling/lexicos/objects?id=usuário) não ficou sem resposta |

## **Áudio**

### Áudio enviado
|           |               |
|-----------|---------------|
| **Nome**  |   [Áudio](/docs/modeling/lexicos/objects?id=áudio) enviado    |
| **Classificação** | Estado |
| **Sinônimos** | [Áudio](/docs/modeling/lexicos/objects?id=áudio) entregue <br> [Mensagem](/docs/modeling/lexicos/objects?id=mensagem) de voz enviada|
| **Noção**     | A [mensagem](/docs/modeling/lexicos/objects?id=mensagem) de [áudio](/docs/modeling/lexicos/objects?id=áudio) foi enviada ao [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> Ocorre quando o [usuário](/docs/modeling/lexicos/objects?id=usuário) aperta no botão de gravar [mensagem de áudio](/docs/modeling/lexicos/objects?id=áudio) |
| **Impacto**   | A [mensagem](/docs/modeling/lexicos/objects?id=mensagem) de [áudio](/docs/modeling/lexicos/objects?id=áudio) ou [mensagem de voz](/docs/modeling/lexicos/objects?id=áudio) foi recebida pelo [usuário](/docs/modeling/lexicos/objects?id=usuário) |

### Áudio pausado
|           |               |
|-----------|---------------|
| **Nome**  |   [Áudio](/docs/modeling/lexicos/objects?id=áudio) pausado    |
| **Classificação** | Estado |
| **Sinônimos** | |
| **Noção**     | O [áudio](/docs/modeling/lexicos/objects?id=áudio) encontra-se interrupto <br> Ocorre quando o [áudio](/docs/modeling/lexicos/objects?id=áudio)está pausado |
| **Impacto**   | Os [usuários](/docs/modeling/lexicos/objects?id=usuário) não conseguem ouvir o [áudio](/docs/modeling/lexicos/objects?id=áudio)durante determinado tempo |

### Áudio em execução
|           |               |
|-----------|---------------|
| **Nome**  |   [áudio](/docs/modeling/lexicos/objects?id=áudio)em execução    |
| **Classificação** | Estado |
| **Sinônimos** | |
| **Noção**     | O [áudio](/docs/modeling/lexicos/objects?id=áudio) encontra-se em execução <br> Ocorre quando você aperta play no [áudio](/docs/modeling/lexicos/objects?id=áudio) |
| **Impacto**   | Os [usuário](/docs/modeling/lexicos/objects?id=usuário)s conseguem escutar o [áudio](/docs/modeling/lexicos/objects?id=áudio) por completo <br> Os [usuários](/docs/modeling/lexicos/objects?id=usuário) conseguem ouvir o [áudio](/docs/modeling/lexicos/objects?id=áudio) durante determinado tempo |

## **Chamadas**

### Microfone mudo
|           |               |
|-----------|---------------|
| **Nome**  |   Microfone mudo   |
| **Classificação** | Estado |
| **Sinônimos** | [Microfone](/docs/modeling/lexicos/objects?id=microfone) silencioso |
| **Noção**     | O [microfone](/docs/modeling/lexicos/objects?id=microfone) está no modo silencioso <br> Ocorre quando o [usuário](/docs/modeling/lexicos/objects?id=usuário) clica no botão de silenciar o [microfone](/docs/modeling/lexicos/objects?id=microfone) |
| **Impacto**   | Os [usuário](/docs/modeling/lexicos/objects?id=usuário)s não conseguem ouvir a pessoa que está com o [microfone](/docs/modeling/lexicos/objects?id=microfone) no estado silencioso |

### Câmera desligada
|           |               |
|-----------|---------------|
| **Nome**  |   [Câmera](/docs/modeling/lexicos/objects?id=câmera) desligada    |
| **Classificação** | Estado |
| **Sinônimos** | [Câmera](/docs/modeling/lexicos/objects?id=câmera) desconectada |
| **Noção**     | A [câmera](/docs/modeling/lexicos/objects?id=câmera) está no modo desligado <br> Ocorre quando o [usuário](/docs/modeling/lexicos/objects?id=usuário) clica no botão de desabilitar a [câmera](/docs/modeling/lexicos/objects?id=câmera) na chamade de [vídeo](/docs/modeling/lexicos/objects?id=vídeo) |
| **Impacto**   | Os [usuário](/docs/modeling/lexicos/objects?id=usuário)s não conseguem ver a pessoa que está com a [câmera](/docs/modeling/lexicos/objects?id=câmera) desabilitada |

## **Mídia**
### Foto enviada
|           |               |
|-----------|---------------|
| **Nome**  |   [Foto](/docs/modeling/lexicos/objects?id=imagem) enviada    |
| **Classificação** | Estado |
| **Sinônimos** | [Foto](/docs/modeling/lexicos/objects?id=imagem) entregue |
| **Noção**     | A [foto](/docs/modeling/lexicos/objects?id=imagem) foi enviada ao [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> Ocorre quando o [usuário](/docs/modeling/lexicos/objects?id=usuário) aperta no botão de enviar a [foto](/docs/modeling/lexicos/objects?id=imagem) |
| **Impacto**   | A [foto](/docs/modeling/lexicos/objects?id=imagem) foi recebida pelo [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> A [foto](/docs/modeling/lexicos/objects?id=imagem) pode ser vista pelo [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> A [foto](/docs/modeling/lexicos/objects?id=imagem) foi entregue ao [usuário](/docs/modeling/lexicos/objects?id=usuário) |

### Vídeo enviado
|           |               |
|-----------|---------------|
| **Nome**  |   [Vídeo](/docs/modeling/lexicos/objects?id=vídeo) enviado    |
| **Classificação** | Estado |
| **Sinônimos** | [Vídeo](/docs/modeling/lexicos/objects?id=vídeo) entregue |
| **Noção**     | O [vídeo](/docs/modeling/lexicos/objects?id=vídeo) foi enviado ao [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> Ocorre quando o [usuário](/docs/modeling/lexicos/objects?id=usuário) aperta no botão de enviar o [vídeo](/docs/modeling/lexicos/objects?id=vídeo) |
| **Impacto**   | O [vídeo](/docs/modeling/lexicos/objects?id=vídeo) foi recebido pelo [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> O [usuário](/docs/modeling/lexicos/objects?id=usuário) pode assistir o [vídeo](/docs/modeling/lexicos/objects?id=vídeo) <br> O [vídeo](/docs/modeling/lexicos/objects?id=vídeo) foi entregue ao [usuário](/docs/modeling/lexicos/objects?id=usuário) |

### Arquivo enviado
|           |               |
|-----------|---------------|
| **Nome**  |   [Arquivo](/docs/modeling/lexicos/objects?id=arquivo) enviado    |
| **Classificação** | Estado |
| **Sinônimos** | [Arquivo](/docs/modeling/lexicos/objects?id=arquivo) entregue |
| **Noção**     | O [arquivo](/docs/modeling/lexicos/objects?id=arquivo) foi enviado ao [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> O [arquivo](/docs/modeling/lexicos/objects?id=arquivo) foi passado ao [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> Ocorre quando o [usuário](/docs/modeling/lexicos/objects?id=usuário) aperta no botão de enviar [arquivo](/docs/modeling/lexicos/objects?id=arquivo) |
| **Impacto**   | O [arquivo](/docs/modeling/lexicos/objects?id=arquivo) foi recebido pelo [usuário](/docs/modeling/lexicos/objects?id=usuário) <br> O [usuário](/docs/modeling/lexicos/objects?id=usuário) pode ver o conteúdo do [arquivo](/docs/modeling/lexicos/objects?id=arquivo) <br> O [arquivo](/docs/modeling/lexicos/objects?id=arquivo) foi entregue ao [usuário](/docs/modeling/lexicos/objects?id=usuário) |
