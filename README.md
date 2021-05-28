
# Análise Hepatite no Brasil (1998 à 2020)


## Introdução
Este projeto propõe realizar uma análise exploratória dos dados relacionados com os vários tipos de hepatites, como óbitos, vacinação e gastos em hospitaos da rede pública de saúde em caso de óbitos decorrentes desta enfermidade, além de relacionar os dados de tamanho da poupução brasieira ao longo do período estudado. Todos os dados foram extraídos do sistema TABNET/DATASUS diponibilizado pelo Governo Federal.

-> [Clique aqui para visualizar o Notebook do Projeto Final](https://github.com/LucasAlbFar/analise_dados_hepatite_brasil/blob/main/notebooks/main.ipynb) <-

## Escopo do Projeto
Este projeto tem como objetivo explorar os dados referentes à epidemias que envolvam algum dos tipos de Hepatite no Brasil, entre os anos de 1998 e 2020, perído do qual foi possível encontrar os dados consolidados disponibilizados pelo DATASUS. 
Visando uma melhor compreensão dos impactos na população e nos gastos com serviços públicos, este projeto visa demonstrar como a Hepatite, uma enfermidade estudada ao longo de décadas e com medidas de prevenção e controle com rigorosas diretrizes, causa transtornos à população e como os órgãos públicos necessitam de constante vigilância para evitar óbitos entre as comunidades menos favorecidas e gastos públicos desenfreados quando o estado falha na educação e prevenção.

## Planejamento do Projeto

Para a realização do projeto, seguirei o seguinte planejamento :

<b> 1.</b> Definição do Problema de Negócio </br>
<b> 2.</b> Preparação dos Dados </br>
<b> 3.</b> Análise Exploratória dos Dados </br>
<b> 4.</b> Criação do Modelo de Machine Learning </br>
<b> 5.</b> Otimização do Modelo de Machine Learning </br>
<b> 6.</b> Apresentação do Resultado </br>

## Dados Utilizados no Projeto

Para o projeto, iremos utilizar duas bases de dados, que são :

- dados_experimentos.zip : Dados com os valores de expressão gênica, viabilidade celular, tratamento, dose, tempo para os diferentes experimentos.
- dados_resultados.csv   : Dados com os valores de ativação ou não do Mecanismo de Ação.

-> [Clique aqui para verificar os dados](https://github.com/gustavolq/Imersao-Dados-Alura/tree/main/Dados) <-


















# Análise de dados sobre hepatite no Brasil, entre os anos de 1998 e 2020

* doses_aplicadas_por_ano_1994_2021.csv
>Imunizações - Doses Aplicadas - Brasil
Doses_aplicadas por Ano segundo Unidade da Federação
Imunobiológicos: Hepatite A (HA) , Hepatite B (HB) , Hepatite B não soroconversão , HEPATITE A, B RECOMBINANTE
Ano: 1994-2021


* valor_total_morbilidade_hospitalar_sus_1995_2007.csv
>Valor Total por Ano processamento segundo Unidade da Federação
Lista Morb CID-10: Hepatite aguda B, Outras hepatites virais
Período: 1995-2007


* valor_total_morbilidade_hospitalar_sus_2008_2021.csv
>Valor total por Ano processamento segundo Unidade da Federação
Lista Morb CID-10: Hepatite aguda B, Outras hepatites virais
Período: Jan/2008-Mar/2021


* morbilidade_hospitalar_sus_2008_2021.csv
>Óbitos por Ano processamento segundo Unidade da Federação
Lista Morb CID-10: Hepatite aguda B, Outras hepatites virais
Período: Jan/2008-Mar/2021


* morbilidade_hospitalar_sus_1995_2007.csv
>Óbitos por Ano processamento segundo Unidade da Federação
Lista Morb CID-10: Hepatite aguda B, Outras hepatites virais
Período: 1995-2007


* populaca_residente_1995_2012.csv
>População residente por Ano segundo Unidade da Federação
Período: 1995-2012


* populaca_residente_2013_2020.csv
>População residente por Ano segundo Unidade da Federação
Período: 2013-2020
Estimativas preliminares elaboradas pelo Ministério da Saúde/SVS/DASNT/CGIAE


* valor_total_procedimentos_hospitalares_1995_2007csv.csv
>Valor total por Ano processamento segundo Unidade da Federação
Período: 1995-2007


* valor_total_procedimentos_hospitalares_2008_2021csv
>Valor total por Ano/mês processamento segundo Unidade da Federação
Período: Jan/2008-Mar/2021
