# Bacia do Rio Doce — Análise Ambiental e Priorização de Áreas

## Sobre o projeto
Este projeto consiste na construção de um fluxo de análise espacial para integração e análise de diferentes conjuntos de dados ambientais na **Bacia Hidrográfica do Rio Doce**.

O projeto utiliza Python e ferramentas de geoprocessamento para preparar, explorar e integrar dados geoespaciais provenientes de diferentes fontes, com o objetivo de estruturar uma abordagem para **identificação e priorização de áreas com potencial para recuperação ambiental**.

O desenvolvimento é realizado de forma incremental, com cada notebook correspondendo a uma etapa específica do fluxo de processamento.

## Objetivo

Construir uma base geoespacial integrada que permita analisar diferentes características ambientais da Bacia do Rio Doce e, posteriormente, apoiar a identificação e priorização de áreas de interesse para recuperação ambiental.

Entre as etapas previstas estão:

- definição e preparação da área de estudo;
- processamento de dados de relevo;
- preparação e análise da hidrografia;
- integração da divisão municipal;
- análise de uso e cobertura da terra;
- caracterização das propriedades do solo;
- integração dos diferentes critérios ambientais;
- desenvolvimento de uma abordagem de priorização espacial.

## Área de estudo

A área de estudo corresponde à **Bacia Hidrográfica do Rio Doce**, delimitada a partir de dados disponibilizados pela Agência Nacional de Águas e Saneamento Básico (ANA).

A preparação da área de estudo constitui a primeira etapa do projeto e estabelece a referência espacial utilizada nas etapas subsequentes.

## Metodologia

O projeto está sendo desenvolvido como um fluxo incremental de processamento geoespacial.

Dados brutos                      
    │                   
    ├── Hidrografia             
    ├── Relevo                      
    ├── Municípios            
    ├── Uso e cobertura da terra               
    └── Solos           
          │                    
          ▼               
Preparação e padronização                
          │                   
          ▼                     
Análise espacial              
          │                   
          ▼                        
Integração dos critérios                
          │                   
          ▼                    
Priorização de áreas                                   

Cada etapa é documentada em um notebook Jupyter, permitindo acompanhar as decisões metodológicas, os procedimentos de processamento e os produtos gerados.

## Estrutura do projeto

Bacia_Rio_Doce/                    
│                    
├── notebooks/                 
│   └── 01_area_estudo.ipynb                
│                    
├── dados/                   
│   ├── brutos/              
│   └── processados/             
│                     
├── mapas/                  
├── scripts/               
├── docs/                 
│                    
├── README.md                 
├── .gitignore               
└── requirements.txt                                

As pastas e os dados são incorporados ao projeto progressivamente, conforme cada etapa do processamento é desenvolvida.

## Tecnologias
- Python                 
- Jupyter Notebook                  
- GeoPandas                     
- Rasterio                                
- Pandas               
- NumPy                   
- Matplotlib
- WhiteboxTools

## Progresso

| Etapa | Descrição                              | Status                |
| ----: | -------------------------------------- | --------------------- |
|    01 | Preparação da área de estudo           | 🟢 Concluída          |
|    02 | Preparação do DEM e dados de relevo    | 🔄 Em desenvolvimento |
|    03 | Preparação da hidrografia              | ⏳ Planejada          |
|    04 | Preparação dos municípios              | ⏳ Planejada          |
|    05 | Preparação do uso e cobertura da terra | ⏳ Planejada          |
|    06 | Preparação dos dados de solo           | ⏳ Planejada          |
|   07+ | Integração e análise dos critérios     | ⏳ Planejada          |


## Resultados

Os produtos gerados em cada etapa são utilizados como entrada para as etapas subsequentes do projeto.

O primeiro produto consiste na delimitação e preparação da Bacia do Rio Doce, disponibilizada em formato GeoPackage para utilização nas análises seguintes.

## Próximas etapas

O desenvolvimento continuará com a preparação dos dados de relevo, seguida pela integração da hidrografia, municípios, uso e cobertura da terra e propriedades do solo.

A etapa final deverá integrar os diferentes critérios ambientais em uma abordagem espacial de priorização.

## Status do projeto

🚧 Projeto em desenvolvimento

A metodologia, os dados e os procedimentos de análise poderão ser refinados ao longo do desenvolvimento do projeto.






