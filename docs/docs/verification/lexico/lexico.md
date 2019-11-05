| Data | Versão | Descrição | Autor |
| --- | --- | --- | --- |
| 04/011/2019 | 1.0 | Criação do documento de verificação dos Léxicos | [Gabriel Alves](https://github.com/gitgabiru) e [Guilherme Mendes](https://github.com/guilherme-mendes) |

## Rastreabilidade

[**Léxicos - Estados**](/docs/modeling/lexicos/states.md)
[**Léxicos - Objetos**](/docs/modeling/lexicos/objects.md)
[**Léxicos - Verbos**](/docs/modeling/lexicos/verbs.md)

## Possíveis erros que podem ser encontrados

![Fagan errors](https://user-images.githubusercontent.com/40740008/67889473-b1681800-fb2d-11e9-9417-8b0d5289b154.jpg)

## Inspeção

|Item|Sim|Não|Tipos de Erro|% de acerto|Objetos para serem corrigidos|
|---|---|---|---|---|---|
|O objeto possui noção|19|0| - |100| - |
|O objeto possui impacto|19|0| - |100| - |
|O objeto indica ter zero ou mais sinônimos|19|0| - |100| - |
|A noção traz significado ao objeto|15|4|Defeito de Omissão, Defeito de Informação Estranha|79|[Microfone](/docs/verification/lexico/objectFix?id=microfone), [Câmera](/docs/verification/lexico/objectFix?id=câmera), Arquivo|
|O impacto descreve o efeito do objeto|19|0| - |100| - |
|É identificado relacionamento com outros objetos|10|9|Defeito de Omissão|52|Áudio, Imagem, Texto, Vídeo, Microfone, Câmera, Arquivo|
|Possui hyperlink|17|2|Defeito de Omissão|89|Administrador, Perfil|