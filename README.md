# Pesquisa Desenvolvimento municipal de São Paulo

> Fonte dos dados do IPDM: <https://repositorio.seade.gov.br/group/indice-paulista-de-desenvolvimento-municipal-ipdm>; 
> Fonte dos dados do PIB: <https://repositorio.seade.gov.br/group/seade-pib>;

O objetivo do projeto é analisar o desenvolvimento do estado de São Paulo a nível municipal, considerando questões como o PIB de cada município e também o IPDM (indíce paulista de desenvolvimento municipal) de cada um. Os dados para essa pesquisa foram obtidos da Fundação Seade - Sistema Estadual de Análise de Dados. É sabido que São Paulo está entre os estados mais ricos do Brasil e que existe uma evidente desigualdade entre os estados, porém será que existe também uma desigualdade entre os municípios dentro do estado? Esta é uma das perguntas que busco responder com essa pesquisa.

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Pesquisa Desenvolvimento Municipal**
| :label: Tecnologias | Python, Seaborn, Pandas, Plotly, Jupyter Notebook

![Gráfico de exemplo](https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/comparacao_ipdm.png?raw=true#vitrinedev)

## Índice de desenvolvimento dos 10 municípios mais populosos

Podemos concluir que nem sempre os municípios mais populosos são os mais desenvolvidos e que o índice de desenvolvimento entre estes mais populosos não possui uma variância alta.

![Gráfico de barras horizontais mostrando o índice de desenvolvimento dos 10 municípios mais populosos](https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/ipdm_10_mais_populosos.png?raw=true)

## Índice de desenvolvimento e PIB da cidade de São Paulo

Através dos seguintes gráficos, podemos concluir que a cidade de São Paulo tem seu PIB proveniente do setor terciário da economia (Serviços) e de valor adicionado, que corresponde ao valor agregado aos bens e serviços consumidos durante o processo produtivo, sendo a diferença entre o valor de produção e o consumo intermediário. Podemos ver também que o índice de desenvolvimento da cidade de São Paulo é de somente 0.59, por conta de seu PIB per capita e escolaridade serem baixas.

![Dois gráficos, um mostrando o PIB de São Paulo por setor e o outro mostrando o índice de desenvolvimento por categoria](https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/desenvolvimento_sp.png?raw=true)

## Série histórica da cidade de São Paulo

É notável o crescimento de São Paulo nos últimos anos, tanto no PIB quanto no índice paulista de desenvolvimento, apresentando uma taxa de crescimento parecida. Podemos perceber que somente a partir de 2020 que temos uma diminuição no IPDM e no PIB, por conta do início da pandemia.

![Dois gráficos, um mostrando o IPDM entre 2014 e 2021 e outro mostrando o PIB entre 2002 e 2020](https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/serie_historica_sp.png?raw=true)

## Série histórica do IPDM dos 10 municípios mais populosos

Através desse gráfico, podemos ver que os municípios tiveram uma tendência parecida, todos estavam com o índice de desenvolvimento melhorando e começaram a diminuir em 2020 por conta da pandemia. Podemos destacar o município de Mauá, que estava com uma taxa de crescimento elevada, porém esta estagnou em 2018, além disso a cidade de Guarulhos além de ser a menos desenvolvida entre as 10, apresenta também uma taxa de crescimento menor em comparação com o resto.

> HTML do gráfico interativo: <https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/serie_historica_ipdm_top_10.html>

![Gráfico mostrando a variação do IPDM dos 10 municípios mais populosos de São Paulo ao longo do tempo](https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/serie_historica_ipdm_top_10.png?raw=true)

## Série histórica do PIB dos 10 municípios mais populosos

A visualização desse gráfico foi prejudicada por conta da diferença enorme entre o PIB de São Paulo e os outros municípios, desde 2002 São Paulo já se destacava dos outros, mas com o tempo essa diferença se tornou ainda maior. Para uma análise mais clara, podemos aplicar filtros no gráfico interativo e excluir a visualização de São Paulo, revelando uma tendência de crescimento em todos os municípios, sobretudo em Osasco, que chegou a alcançar 80 bilhões de PIB em 2019.

> HTML do gráfico interativo: <https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/serie_historica_pib_top_10.html>

![Gráfico mostrando a variação do PIB dos 10 municípios mais populosos de São Paulo ao longo do tempo](https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/serie_historica_pib_top_10.png?raw=true)

## Histograma do PIB per capita dos municípios em 2020

Podemos ver que a maior parte dos municípios possui um PIB per capita em torno de 50 mil reais, porém existem alguns municípios que se destacam por possuir um PIB per capita extremamente alto, como o município de Louveira, que apresenta um PIB per capita de mais de 360 mil reais.

![Histograma mostrando a distribuição de frequência do PIB per capita dos municípios](https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/histograma_pib_per_capita.png?raw=true)

## Comparando o PIB per capita dos 10 municípios mais populosos em 2020

É notável que o PIB per capita de Osasco é muito maior que os dos outros municípios analisados, sendo de 112 mil reais. Podemos destacar também o município de São Paulo, que apesar de ter o PIB altíssimo, conta com uma população muito grande e portanto acaba tendo o PIB per capita mediano, próximo a 63 mil reais. O resto dos municípios se encontra na faixa entre 50 e 60 mil reais, sendo o município de Mauá, que anteriormante apresentava um bom crescimento, aquele com o menor PIB per capita, de somente 37 mil reais.

> HTML do gráfico interativo: <https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/pib_per_capita_top_10.html>

![Gráfico de barras mostrando o PIB per capita dos municípios](https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/pib_per_capita_top_10.png?raw=true)

## Comparando os municípios com o maior e o menor IPDM em 2021

O município com maior IPDM de SP é Águas de São Pedro, sendo de 0,687. Águas de São Pedro é o menor município de SP e é famoso por suas estâncias hidrominerais, possuindo só um distrito dividido em 4 partes. Já Guapiara é o município com o menor IPDM, de somente 0,366. Guapiara é um município do interior de SP conhecido como a Capital do Artesanato e do Pêssego.

![Gráficos de barras mostrando o IPDM dos municípios mais e menos desenvolvidos](https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/comparacao_ipdm.png?raw=true)

## Comparando os municípios com o maior e o menor PIB de 2020

O município mais rico de SP é a capital São Paulo, com um PIB de quase 750 bilhões de reais em 2020. O PIB de São Paulo provém principalmente dos setores de Valor adicionado, Serviços e Impostos líquidos, sendo que o setor de Agropecuária representa menos de 1% de seu PIB. Já o município com o menor PIB é Torre de Pedra, com um PIB de somente 34 milhões de reais. O PIB de Torre de Pedra apresenta uma distribuição parecida com a de São Paulo, uma das diferenças é que o Setor de Serviços de Administração pública representam mais de 20% do PIB de Torre de Pedra, setor esse que não representa nem 4% do PIB de São Paulo. Torre de Pedra é um município pequeno de por volta de 72km² e 2500 habitantes, seu nome vem de uma elevação rochosa que existe na sua região rural.

![Gráficos de pizza comparando a distribuição do PIB dos municípios mais e menos ricos](https://github.com/BrenoMorim/pesquisa-sao-paulo/blob/main/graficos/comparacao_pib.png?raw=true)

---
