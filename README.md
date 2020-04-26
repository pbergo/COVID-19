# COVID-19

 Análise da evolução do COVID-19

## Descrição

Essa aplicação foi construída para realizar análises e projeções do COVID-19, uma doença de proporções pandêmicas.

![COVID-19](https://github.com/pbergo/COVID-19/blob/master/COVID-19-Geral.gif)

Os dados são obtidos através de diveras fontes:

* Casos mundiais do projeto JJHS: 
* <https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv> 
* <https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv>
* <https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv>
* Casos do Brasil: <https://brasil.io/dataset/covid19/caso>
* Municípios (*): <ftp://geoftp.ibge.gov.br/organizacao_do_territorio/estrutura_territorial/divisao_territorial/2018/DTB_2018.zip>
* População (*): <https://www.ibge.gov.br/estatisticas/sociais/populacao/9103-estimativas-de-populacao.html?=&t=downloads>
* Leitos disponíveis por Municípios (*): <http://tabnet.datasus.gov.br/cgi/deftohtm.exe?cnes/cnv/leiutibr.def>

Para construir esse painel, usei como base a contribuição da comunidade [Qlik Community COVID group](https://community.qlik.com/t5/COVID-19/gp-p/covid-19-group), além de contribuição dos colegas da empresa [ADITI GESTÃO E TI LTDA](https://aditi.com.br).

Mais detalhes sobre o COVID-19, pode ser encontrado na página da [Organização Mundial da Saúde](https://www.who.int/emergencies/diseases/novel-coronavirus-2019) e também do [Ministério da Saúde do Brasil](https://coronavirus.saude.gov.br).

Essa aplicação foi desenvolvida na versão Qlik Sense February 2020.

(*) Dados baixados manualmente e disponibilizados no Github para acesso pela app

## Fontes de dados desativadas

As fontes a seguir foram desativadas:

* Projeto Github: <https://github.com/jmcastagnetto/covid-19-data-cleanup>
* Casos acumulados: <https://raw.githubusercontent.com/jmcastagnetto/covid-19-data-cleanup/master/data/covid-19_ts_combined.csv.gz>
* Casos em tempo real: <https://www.worldometers.info/coronavirus/>

## Downloads

* Qlik Sense Desktop February 2020 Patch 1: <https://da3hntz84uekx.cloudfront.net/QlikSenseDesktop/13.62/1/_MSI/Qlik_Sense_Desktop_setup.exe>

## Instruções de Instalação

1. Baixe e instale o Qlik Sense Desktop versão February 2020
2. Descompacte as extensões (arquivos zip) constante na pasta Extensions para o diretório %HOMEPATH%\Documents\QLIK\Sense\Extensions.
3. Copie o arquivo COVID-19.qvf para diretório %HOMEPATH%\Documents\QLIK\Sense\Apps
