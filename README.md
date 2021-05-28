
# Análise Hepatite no Brasil (1998 à 2020)


## Introdução
Este projeto propõe realizar uma análise exploratória dos dados relacionados com os vários tipos de hepatites, como óbitos, vacinação e gastos em hospitaos da rede pública de saúde em caso de óbitos decorrentes desta enfermidade, além de relacionar os dados de tamanho da poupução brasieira ao longo do período estudado. Todos os dados foram extraídos do sistema TABNET/DATASUS diponibilizado pelo Governo Federal.

-> [Clique aqui para visualizar o Notebook do Projeto Final](https://github.com/LucasAlbFar/analise_dados_hepatite_brasil/blob/main/notebooks/main.ipynb) <-

## Objetivo do Projeto
Este projeto tem como objetivo explorar os dados referentes à epidemias que envolvam algum dos tipos de Hepatite no Brasil, entre os anos de 1998 e 2020, perído do qual foi possível encontrar os dados consolidados disponibilizados pelo DATASUS. 
Visando uma melhor compreensão dos impactos na população e nos gastos com serviços públicos, este projeto visa demonstrar como a Hepatite, uma enfermidade estudada ao longo de décadas e com medidas de prevenção e controle com rigorosas diretrizes, causa transtornos à população e como os órgãos públicos necessitam de constante vigilância para evitar óbitos entre as comunidades menos favorecidas e gastos públicos desenfreados quando o estado falha na educação e prevenção.

## Dados Utilizados
Abaixo estão os dados utilizados para a análise da hepatite no Brasil:

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

-> [Clique aqui para verificar os dados](https://github.com/LucasAlbFar/analise_dados_hepatite_brasil/tree/main/dados) <-


## Breve overview sobre a Hepatite
As hepatites virais são um grave problema de saúde pública no Brasil e no mundo. É uma infecção que atinge o fígado, causando alterações leves, moderadas ou graves. Na maioria das vezes são infecções silenciosas, ou seja, não apresentam sintomas. Entretanto, quando presentes, podem se manifestar como: cansaço, febre, mal-estar, tontura, enjoo, vômitos, dor abdominal, pele e olhos amarelados, urina escura e fezes claras.
Cristiane Bomfim

Responsáveis por 1,3 milhão de mortes por ano no mundo, segundo estimativa da OMS (Organização Mundial da Saúde), as hepatites virais são inflamações que aos poucos matam as células do fígado e as transformam em cicatrizes que enrijecem o tecido, chamadas de fibrose. Sem apresentar sintomas, a evolução é, na maioria dos casos, silenciosa. Por isso, muitas vezes é descoberta quando está em estágio avançado, já com o comprometimento da função do fígado, cirrose ou mesmo o câncer. E embora os vírus sejam os principais causadores da hepatite, ela também pode ser resultado do uso de substâncias tóxicas (como alguns remédios), exagero no consumo de álcool e doenças autoimunes, genéticas e metabólicas.

### Tipos de Hepatites:
<b> Hepatite A </b>
