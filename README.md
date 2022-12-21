# Tarifas Aéreas Domésticas - Aeroporto do Recife - SBRF
Repositório do projeto de análise da venda e preço das passagens aéreas a partir do Aeroporto do Recife(REC-SBRF). Utilizando Python e a biblioteca Pandas para extração e transformação inicial e o Power BI para refinamento, criação de medidas e dashborad.

Para a análise foi utilizado os dados do DataSAS da ANAC(Agência Brasileira de Aviação Civil) contendo a venda de assentos a partir de janeiro de 2018 até agosto de 2022.

Salientando que segundo a ANAC: "Os dados de tarifas aéreas domésticas abrangem todas as passagens vendidas ao 'público adulto em geral', excluindo aquelas adquiridas com descontos restritos a grupos específicos, programas de milhagem, entre outras condições. O número de assentos vendidos registrados corresponde a cerca de 50% do movimento de passageiros pagos transportados. Ressalva-se que tais bases de dados confrontadas foram concebidas com distintos propósitos, público-alvo e metodologia de apuração que ocasionam diferenças significativas em termos quantitativos."

## Dashboard do projeto:
:bar_chart: [Link para o Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZmY4MDcyZjMtNzVhOC00ZjUzLWJlZDYtNWU0MThjODk0MDlhIiwidCI6IjBjMTUyNDhkLTFiYjMtNDE2Yi1hODJkLTUyOTgxZWUwMzc2NSJ9)

## Índice:

:file_folder: **datasets**
  - **companhias.csv** - *CSV contendo o código, nome e logo  da companhia*
  - **df_lista_oaci.csv** - *CSV contendo o código, estado, município, longitude e latitude do aeroporto*
  - **flights_sbrf_2018-01_2022-09.csv** - *CSV contendo voos com origem no aeroporto do Recife SBRF*
  
 :file_folder: **img**
- **Avianca.png** - *Arquivos PNG do logo da companhia Avianca*
- **Itapemirim.png** - *Arquivos PNG do logo da companhia Itapemirim*
- **azul_logo.png** - *Arquivos PNG do logo da companhia Azul*
- **gol.png** - *Arquivos PNG do logo da companhia Gol*
- **latam.png** - *Arquivos PNG do logo da companhia Latam*
- **menu_sanduiche.png** - *Arquivos PNG do menu sanduíche usado no dashboard*

 :file_folder: **jupyter**
 - **com_erros_comentados.ipynb** - *Arquivo jupyter com o passo a passo da transformação dos dados comentados*
 - **extract_sbrf.ipynb** - *Arquivo jupyter com os códigos de extração tratado*
 - **lista_aerodromos.ipynb** - *Arquivo jupyter com a transformação da lista de aeroportos*
  
:page_facing_up: **pbi_dash_voos.pbix** - *Arquivo do projeto Power BI*
