# Verificação NFR Framework

## Checklist de verificação

* Cada softgoal possui um tipo e um tópico?
* Softgoals abstratos são decompostos em subtópicos com softgoals mais específicos?
* Softgoals são decompostos em operacionalizações?
* As operacionalizações podem ser usadas como especificações do sistema?
* As operacionalizações podem ser selecionadas para garantir um resultado viável do sistema?
* A direção da interdependência entre operacionalizações e softgoals vai do mais concreto para o mais abstrato?
* Há a adição de claims para justificar os softgoals quando necessário?
* Contribuições and somente entre softgoals?
* Contribuições or somente entre softgoals?
* Contribuições positivas somente entre os softgoals e as operacionalizações?
* Contribuições negativas somente entre os softgoals e as operacionalizações?
* Os softgoals e as operacionalizações foram classificados a partir de labels?
* A propagação das labels foi feita corretamente?

## Tipos de Erro

|Código|Tipo de Erro|Descrição|
|---|---|---|
| 1 | Defeito de Omissão | Informações necessárias ao sistema são omitidas |
| 2 | Defeito de Fato Incorreto | Há informações nos artefatos do sistema que são contraditórios com o domínio da aplicação |
| 3 | Inconsistência | Informação aparece mais de uma vez de formas diferentes |
| 4 | Ambiguidade | Informação leva múltiplas interpretações |
| 5 | Defeito de Informação Estranha | Informação que aparece no artefato e, embora relacionada, não é necessária para o sistema |

[**NFR de Usabilidade**](/docs/verification/NFR/NFR_usabilidade_verify.md) <br>
[**NFR de Eficiência**](/docs/verification/NFR/NFR_eficiencia_verify.md) <br>
[**NFR de Confiabilidade**](/docs/verification/NFR/NFR_confiabilidade_verify.md) <br>

## Referência
* [Extending the NFR Framework with Measurable NonFunctional Requirements](https://pdfs.semanticscholar.org/4ab6/c7def9be016130684ae615d5bd6ae0e04992.pdf)
* Goal Achievement Evaluation in the NFR Framework, by Sam Supakkul and Lawrence Chung
* [Verificação NFR - Habitica](https://requisitos-habitica.herokuapp.com/VerificacaoNFR)

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

