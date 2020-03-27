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

1. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/jan_fev_mar/02-03-BoletimCoronavirus.pdf>
2. <https://www.saude.mg.gov.br/images/Boletim_Coronavírus_03-03-20.pdf>
3. <https://www.saude.mg.gov.br/component/gmg/story/12217-nota-informativa-coronavirus-04-03-2020>
4. <https://www.saude.mg.gov.br/component/gmg/story/12220-nota-informativa-coronavirus-05-03-2020>
5. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/Coronavírus/Novo_Boletim_Coronavírus_06-03.pdf>
6. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/Coronavírus/Novo_Boletim_Coronavírus_09-03.pdf>
7. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/jan_fev_mar/10-03-BOLETIM-COES-COVID-MG10-03-2020.pdf>
8. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/Coronavírus/BOLETIM_COES_COVID_MG_19_-_11-03-2020.pdf>
9. <https://www.saude.mg.gov.br/images/BOLETIM_COES_COVID_MG_19_-_12-03-2020.pdf>
10. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/jan_fev_mar/13-03-BOLETIM_COES_COVID_MG19.pdf>
11. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/Coronavírus/BOLETIM_COES_COVID_MG_19_-_14-03-2020_ret.pdf>
12. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/Coronavírus/BOLETIM_COES_COVID_MG_19_-_16-03-2020_2.pdf>
13. <https://saude.mg.gov.br/images/noticias_e_eventos/000_2020/Coronavírus/BOLETIM_COES_COVID_MG_19_-_17-03-2020.pdf>
14. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/BOLETIM_COES_COVID_MG_19_-_18-03-2020_16h54.pdf>
15. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/BOLETIM_COES_COVID_MG_19-03-2020.pdf>
16. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/Boletins_Corona/BOLETIM_COES_COVID_MG_20-03-2020.pdf>
17. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/Boletins_Corona/BOLETIM_COES_COVID_MG_21-03-2020_1812-compactado.pdf>
18. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/Boletins_Corona/Informe_epidemiológico_-_22.03.2020.pdf>
19. <https://www.saude.mg.gov.br/images/noticias_e_eventos/000_2020/Boletins_Corona/Informe_epidemiológico_-_22.03.2020.pdf>
20. <https://saude.mg.gov.br/images/noticias_e_eventos/000_2020/Boletins_Corona/boletim_epidemiológico_23.03.2020_-17h20.pdf>

## Downloads

* Qlik Sense Desktop February 2020 Patch 1: <https://da3hntz84uekx.cloudfront.net/QlikSenseDesktop/13.62/1/_MSI/Qlik_Sense_Desktop_setup.exe>

## Instruções de Instalação

1. Baixe e instale o Qlik Sense Desktop versão February 2020
2. Descompacte as extensões (arquivos zip) para o diretório %HOMEPATH%\Documents\QLIK\Sense\Extensions.
3. Copie o arquivo COVID-19.qvf para diretório %HOMEPATH%\Documents\QLIK\Sense\Apps
