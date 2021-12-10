# ibge-cidades
Base de municípios do IBGE em JSON

## Estrutura

O arquivo [municipios.json](municipios.json) é um array de objetos em JSON, onde cada propriedade é uma `string`.

As seguintes propriedades estão disponíveis em cada objeto:
- `_id`
- `ufCodigo`
- `ufNome`
- `ufSigla`
- `mesorregiaoCodigo`
- `mesorregiaoNome`
- `microrregiaoCodigo`
- `microrregiaoNome`
- `municipioCodigo`
- `municipioCodigoAbreviado`
- `municipioNome`

A última atualização contém **5.770 municípios**.

## _id
A propriedade `_id` é uma chave primária sugerida para uso em banco de dados. É obtida a partir da concatenação de `municipioNome` + `, ` + `ufSigla`.
