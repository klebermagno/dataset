# Dataset

a lot of dataset to big data


## International

http://archive.ics.uci.edu/ml/index.php

https://www.kaggle.com/datasets

https://registry.opendata.aws

http://dataportals.org

https://opendatamonitor.eu/frontend/web/index.php?r=dashboard%2Findex

https://www.quandl.com

https://en.wikipedia.org/wiki/List_of_datasets_for_machine_learning_research

https://www.quora.com/Where-can-I-find-large-datasets-open-to-the-public

https://www.reddit.com/r/datasets/

https://data.humdata.org/

https://data.world/

https://catalog.data.gov

https://old.datahub.io

## Brazilian

http://dados.gov.br/

http://www.portaldatransparencia.gov.br

https://data.humdata.org/group/bra

https://data.world/datasets/brazil

https://dadosabertos.bcb.gov.br/en/dataset

https://downloads.ibge.gov.br

https://downloads.ibge.gov.br/downloads_top.php

http://dados.mj.gov.br/dataset

- [QEdu](http://www.qedu.org.br) &mdash; Dados de educação.
- [TIC Pesquisas](http://cetic.br/pesquisas) &mdash; Pesquisas sobre educação, saúde, etc.
- [IBGE](http://www.ibge.gov.br) &mdash; Dados do Instituto brasileiro de geografia e estatística.
- [Datapedia](http://www.datapedia.info) &mdash; Dados organizados por região.
- [Instituto Nacional de Pesquisas Espaciais](http://sinda.crn2.inpe.br/PCD/SITE/novo/site) &mdash; Dados de clima.
- [Infraero](https://github.com/ehrhardt/Infraero) &mdash; Dados da Infraero (Python).
- [congressbr](https://github.com/RobertMyles/congressbr) &mdash; Dados do senado federal e câmara dos deputados (R).
- [places.br](https://github.com/paulofreitas/places.br) &mdash; Dados geográficos.
- [flora](https://github.com/gustavobio/flora) &mdash; Dados da flora brasileira (R).
- [BrazilianFootball](https://github.com/DiSiqueira/BrazilianFootball) &mdash; Dados de futebol (shell script).
- [openfootball/br-brazil](https://github.com/openfootball/br-brazil) &mdash; Dados do campeonato brasileiro.


# Contents

- [Brasil](#Brazilian)
- [Acre](#acre)
- [Alagoas](#alagoas)
- [Amapá](#amapá)
- [Amazonas](#amazonas)
- [Bahia](#bahia)
- [Ceará](#ceará)
- [Distrito Federal](#distrito-federal)
- [Espírito Santo](#espírito-santo)
- [Goiás](#goiás)
- [Maranhão](#maranhão)
- [Mato Grosso](#mato-grosso)
- [Mato Grosso do Sul](#mato-grosso-do-sul)
- [Minas Gerais](#minas-gerais)
- [Pará](#pará)
- [Paraíba](#paraíba)
- [Paraná](#paraná)
- [Pernambuco](#pernambuco)
- [Piauí](#piauí)
- [Rio de Janeiro](#rio-de-janeiro)
- [Rio Grande do Norte](#rio-grande-do-norte)
- [Rio Grande do Sul](#rio-grande-do-sul)
- [Rondônia](#rondônia)
- [Roraima](#roraima)
- [Santa Catarina](#santa-catarina)
- [São Paulo](#são-paulo)
- [Sergipe](#sergipe)
- [Tocantins](#tocantins)




## Acre

## Alagoas

- [Alagoas em Dados e Informações](http://dados.al.gov.br) &mdash; Dados e informações socioeconômicas de Alagoas.

## Amapá

## Amazonas

## Bahia

## Ceará

- [SEDUC](http://dados.seduc.ce.gov.br) &mdash; Dados de educação do Ceará.
- [Dados Prefeitura de Fortaleza](http://dados.fortaleza.ce.gov.br) &mdash; Dados abertos da Prefeitura de Fortaleza.

## Distrito Federal

## Espírito Santo

## Goiás

## Maranhão

## Mato Grosso

## Mato Grosso do Sul

## Minas Gerais

## Pará

## Paraíba

- [Dados do Estado da Paraíba](http://dados.pb.gov.br) &mdash; Dados que compõem o portal de transparência do Estado da Paraíba.

## Paraná

- [IPARDES](http://www.ipardes.gov.br) &mdash; Dados do instituto paranaense de desenvolvimento econômico e social.

## Pernambuco

- [Dados Prefeitura do Recife](http://dados.recife.pe.gov.br) &mdash; Dados de secretarias e orgãos de gestão municipal.
- [Dados abertos de Pernambuco](www.dadosabertos.pe.gov.br) &mdash; Dados abertos do governo estadual.

## Piauí

## Rio de Janeiro

- [Dados Prefeitura do Rio de Janeiro](http://data.rio) &mdash; Dados de escolas, estabelecimentos de saúde, etc.

## Rio Grande do Norte

## Rio Grande do Sul

- [Dados abertos do Rio Grande do Sul](http://dados.rs.gov.br) &mdash; Dados de orgãos púplicos estaduais.

## Rondônia

## Roraima

## Santa Catarina

- [Santa Catarina](http://www.transparencia.sc.gov.br)

## São Paulo

- [Dados Prefeitura de São Paulo](http://dados.prefeitura.sp.gov.br) &mdash; Dados de orgãos e entidades de administração municipal.

## Sergipe

## Tocantins

# Tools

To merge many files in one. To easy import file.

$awk 'FNR==1 && NR!=1{next;}{print}' *.csv
