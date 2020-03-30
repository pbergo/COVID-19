# COVID-19

 Análise da evolução do COVID-19

## Descrição

Essa aplicação foi construída para realizar análises e projeções do COVID-19, uma doença de proporções pandêmicas.

![COVID-19](https://github.com/pbergo/COVID-19/blob/master/COVID-19-Geral.gif)

Os dados são obtidos através de diveras fontes:

* Projeto Github: <https://github.com/jmcastagnetto/covid-19-data-cleanup>
* Casos acumulados: <https://raw.githubusercontent.com/jmcastagnetto/covid-19-data-cleanup/master/data/covid-19_ts_combined.csv>
* Casos em tempo real: <https://www.worldometers.info/coronavirus/>
* Casos do Brasil: <https://brasil.io/dataset/covid19/caso>
* Municípios (*): <ftp://geoftp.ibge.gov.br/organizacao_do_territorio/estrutura_territorial/divisao_territorial/2018/DTB_2018.zip>
* População (*): <https://www.ibge.gov.br/estatisticas/sociais/populacao/9103-estimativas-de-populacao.html?=&t=downloads>
* Leitos disponíveis por Municípios (*): <http://tabnet.datasus.gov.br/cgi/deftohtm.exe?cnes/cnv/leiintbr.def>

Para construir esse painel, usei como base a contribuição de [Luis Felipe Tensini](https://www.linkedin.com/in/tensini/) e seu post de [Análise Básica do COVID-19 com Qlik Sense](https://www.linkedin.com/posts/tensini_qlik-coronavirus-activity-6643295124241567744-D1Ao).

Mais detalhes sobre o COVID-19, pode ser encontrado na página da [OMS](https://www.who.int/emergencies/diseases/novel-coronavirus-2019) e também do [MS do Brasil](https://coronavirus.saude.gov.br).

Essa aplicação foi desenvolvida na versão Qlik Sense February 2020.

(*) Dados baixados manualmente e disponibilizados no Github para acesso pela app

## Fontes Desativadas

As fontes a seguir foram desativadas para ampliar os dados apresentados
* Planilha com os boletins compilados: <https://docs.google.com/spreadsheets/d/1FkHAnOTVGxrVrxPRpFOgsIjCxqk28ERIXz1kt56dtEQ/edit?usp=sharing>
* Página com todos os Informes Epidemiológicos sobre o Coronavírus da SES-MG:<https://www.saude.mg.gov.br/component/search/?all=%22informe+epidemiol%C3%B3gico+coronav%C3%ADrus%22&area=all>
* Aplicativo da SES-MG que apresenta os dados diários: <https://docs.google.com/spreadsheets/d/e/2PACX-1vSJ-sTSKNGPaxqrVTkccEWG0bc8-LdGtlPEXc8qkUI3o7KM0CFmuRMW6UoqPrYID_JDpzGMGWng637S/pubhtml>

## Downloads

* Qlik Sense Desktop February 2020 Patch 1: <https://da3hntz84uekx.cloudfront.net/QlikSenseDesktop/13.62/1/_MSI/Qlik_Sense_Desktop_setup.exe>

## Instruções de Instalação

1. Baixe e instale o Qlik Sense Desktop versão February 2020
2. Descompacte as extensões (arquivos zip) constante na pasta Extensions para o diretório %HOMEPATH%\Documents\QLIK\Sense\Extensions.
3. Copie o arquivo COVID-19.qvf para diretório %HOMEPATH%\Documents\QLIK\Sense\Apps
