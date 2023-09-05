# Projeto_Cafe

## Armazenamento
### 1. Criação de Bucket S3
[AWS_S3_CreateBucket](Codigos/AWS_S3_CreateBucket.ipynb)

Código python para criação de um Bucket S3 na AWS com o nome "conab-dados"

![Create Bucket S3](Images/CreateBucketS3.jpg)

## Inserção de dados
### 1. WebScrapping de dados para popular o S3 criado
[AWS_S3_WebScraping](Codigos/AWS_S3_WebScraping.ipynb)

Código python para realizar um WebScrapping dos dados do café do Conab (Companhia Nacional de Abastecimento), arquivos no formato .pdf de relatórios da produção de café nacional. Posteriormente, realizar a ingestão desses arquivos em formato cru (archive.pdf) para uma pasta "Arquivos Conab/" dentro do Bucket S3 "conab-dados".

![WebSrape](Images/WebScrape.jpg)
