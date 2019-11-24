| Data | Versão | Descrição | Autor |
| --- | --- | --- | --- |
| 04/11/2019 | 1.0 | Criação do documento de verificação dos Léxicos (objetos) | [Gabriel Alves](https://github.com/gitgabiru) |

## Rastreabilidade

[**Léxicos - Objetos**](/docs/modeling/lexicos/objects.md)

## Possíveis erros que podem ser encontrados

![tabela de defeitos](https://user-images.githubusercontent.com/40740008/68208095-311f3800-ffaf-11e9-9592-82ae6efa30bc.jpg)

## Inspeção

|Item|Sim|Não|Tipos de Erro|% de acerto|Objetos para serem corrigidos|
|---|---|---|---|---|---|
|O objeto possui noção|19|0| - |100| - |
|O objeto possui impacto|19|0| - |100| - |
|O objeto indica ter zero ou mais sinônimos|19|0| - |100| - |
|A noção traz significado ao objeto|15|4|Defeito de Omissão, Defeito de Informação Estranha|79|[Microfone](/docs/verification/objectFix/objects?id=microfone), [Câmera](/docs/verification/objectFix/objects?id=camera), [Arquivo](/docs/verification/objectFix/objects?id=arquivo)|
|O impacto descreve o efeito do objeto|19|0| - |100| - |
|É identificado relacionamento com outros objetos|10|9|Defeito de Omissão|52|[Áudio](/docs/verification/objectFix/objects?id=A1udio), [Imagem](/docs/verification/objectFix/objects?id=imagem), [Texto](https://github.com/Requisitos-de-Software/2019.2-Wire/blob/65-VerificacaoLexicos/docs/docs/verification/lexico/objectFix.md#texto), [Vídeo](/docs/verification/objectFix/objects?id=Video), [Microfone](/docs/verification/objectFix/objects?id=microfone), [Câmera](/docs/verification/objectFix/objects?id=Camera), [Arquivo](/docs/verification/objectFix/objects?id=arquivo)|
|Possui hyperlink|17|2|Defeito de Omissão|89|[Administrador](/docs/verification/objectFix/objects?id=arquivo), [Perfil](/docs/verification/objectFix/objects?id=perfil)|

## Gráficos dos resultados

<div class="row">
  <div class="column">
    <img width="349" alt="Screen Shot 2019-10-30 at 14 49 59" src="https://user-images.githubusercontent.com/26935152/68178623-7457b780-ff6b-11e9-9d53-90df89fcbd1a.png">
  </div>
  <div class="column">
    <img width="349" alt="Screen Shot 2019-10-30 at 14 56 05" src="https://user-images.githubusercontent.com/26935152/68178632-7de11f80-ff6b-11e9-892b-1e77351c5abd.png">
  </div>
</div>
<br>
<div class="row">
  <div class="column">
    <img width="349" alt="Screen Shot 2019-10-30 at 14 49 59" src="https://user-images.githubusercontent.com/26935152/68178638-83d70080-ff6b-11e9-916e-3d6bc18c108d.png">
  </div>
  <div class="column">
    <img width="349" alt="Screen Shot 2019-10-30 at 14 56 05" src="https://user-images.githubusercontent.com/26935152/68178642-8a657800-ff6b-11e9-9c65-4cb470e89f48.png">
  </div>
</div>
<br>
<div class="row">
  <div class="column">
    <img width="349" alt="Screen Shot 2019-10-30 at 14 49 59" src="https://user-images.githubusercontent.com/26935152/68178644-8fc2c280-ff6b-11e9-84cd-6a75160d3cff.png">
  </div>
  <div class="column">
    <img width="349" alt="Screen Shot 2019-10-30 at 14 56 05" src="https://user-images.githubusercontent.com/26935152/68178651-96513a00-ff6b-11e9-9307-ea01cab4f7e1.png">
  </div>
</div>
<br>
<div class="row">
  <div class="column">
    <img width="349" alt="Screen Shot 2019-10-30 at 14 49 59" src="https://user-images.githubusercontent.com/26935152/68178660-9cdfb180-ff6b-11e9-9ad8-aae1684abd2f.png">
  </div>

## Referências

* ANTUNES, I. Território das palavras: estudo do léxico em sala de aula. São Paulo: Parábola Editorial, 2012.
* BIDERMAN, M.T.C. Teoria linguística: teoria lexical e teoria computacional. São Paulo: Martins Fontes, 2001.

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