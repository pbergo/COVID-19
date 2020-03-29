# COVID-19

 Análise da evolução do COVID-19

## Descrição

Essa aplicação foi construída para realizar análises e projeções do COVID-19, uma doença de proporções pandêmicas.

![COVID-19](https://github.com/pbergo/COVID-19/blob/master/COVID-19-Geral.gif)

Os dados são obtidos através do site do [Jesus M. Castagnetto](https://castagnetto.site/), um pesquisador peruano, especialista em Bioinformatica. Ele criou um projeto que faz o tratamento e limpeza diária dos dados a partir do site da OMS. Também extraio os dados mais recentes a partir do site WorldoMeters que apresenta resultados em tempo real, e que são acrescentados ao conjunto de dados acumulados para ter um acompanhamento dentro do mesmo dia da análise.

* Projeto Github: <https://github.com/jmcastagnetto/covid-19-data-cleanup>
* Fonte de Dados acumulada: <https://raw.githubusercontent.com/jmcastagnetto/covid-19-data-cleanup/master/data/covid-19_ts_combined.csv>
* Fonte de Dados do dia: <https://www.worldometers.info/coronavirus/>

Para construir esse painel, usei como base a contribuição de [Luis Felipe Tensini](https://www.linkedin.com/in/tensini/) e seu post de [Análise Básica do COVID-19 com Qlik Sense](https://www.linkedin.com/posts/tensini_qlik-coronavirus-activity-6643295124241567744-D1Ao).

Mais detalhes sobre o COVID-19, pode ser encontrado na página da [OMS](https://www.who.int/emergencies/diseases/novel-coronavirus-2019) e também do [MS do Brasil](https://coronavirus.saude.gov.br).

Essa aplicação foi desenvolvida na versão Qlik Sense February 2020.

## Fontes de dados do SES-MG

O dados do SES-MG são obtidos através de arquivos PDF dos Boletins Diários Epidemiológicos, atualizados diariamente e gerados numa planilha da empresa.

* Planilha com os boletins compilados: <https://docs.google.com/spreadsheets/d/1FkHAnOTVGxrVrxPRpFOgsIjCxqk28ERIXz1kt56dtEQ/edit?usp=sharing>
* Página com todos os Informes Epidemiológicos sobre o Coronavírus da SES-MG:<https://www.saude.mg.gov.br/component/search/?all=%22informe+epidemiol%C3%B3gico+coronav%C3%ADrus%22&area=all>
* Aplicativo da SES-MG que apresenta os dados diários: <https://docs.google.com/spreadsheets/d/e/2PACX-1vSJ-sTSKNGPaxqrVTkccEWG0bc8-LdGtlPEXc8qkUI3o7KM0CFmuRMW6UoqPrYID_JDpzGMGWng637S/pubhtml>

## Downloads

* Qlik Sense Desktop February 2020 Patch 1: <https://da3hntz84uekx.cloudfront.net/QlikSenseDesktop/13.62/1/_MSI/Qlik_Sense_Desktop_setup.exe>

## Instruções de Instalação

1. Baixe e instale o Qlik Sense Desktop versão February 2020
2. Descompacte as extensões (arquivos zip) para o diretório %HOMEPATH%\Documents\QLIK\Sense\Extensions.
3. Copie o arquivo COVID-19.qvf para diretório %HOMEPATH%\Documents\QLIK\Sense\Apps
