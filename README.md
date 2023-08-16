<h1 align="center">
  Pipeline Databricks Azure
</h1>

# Indice
- [Sobre](#-Sobre)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- Imagens do projeto



## 🗒 Sobre


Projeto desenvolvido no curso Databricks e Data Factory: criando e orquestrando pipelines na nuvem - Alura

Estrutura do pipeline
Esse pipeline está estruturado da seguinte maneira:
Primeiramente, temos um Data Lake, utilizando o recurso do Data Lake Gen2 da própria Azure. Esse Data Lake vai ser estruturado em três camadas:

Camada Inbound;
Camada Bronze.
Camada Silver.
A camada Inbound é a camada de entrada, onde adicionamos os dados na versão bruta. Os dados que recebemos vão ser dados de imóveis, já que trabalhamos em uma empresa imobiliária.

Com esses dados na nossa camada de entrada, vamos utilizar a ferramenta Databricks para aplicar determinadas transformações nesses dados e passá-los pelas camadas Bronze e Silver do Data Lake.

Uma vez que temos todo esse fluxo de dados estruturado, utilizamos uma ferramenta chamada Azure Data Factory para orquestrar e automatizar a execução desse pipeline de acordo com o intervalo de tempo definido pela empresa.
<h1 align="center">
  <img src="/estrutura da pipeline.PNG">
</h1>

## 🔗  Tecnologias utilizadas

- [Cloud da Azure](https://azure.microsoft.com/pt-pt/')
- [Data Factory]([https://spring.io/projects/spring-boot](https://azure.microsoft.com/pt-br/products/data-factory)')
- [Azure Data Lake Storage Gen 2]([http://hsqldb.org/](https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction)')
- [Scala]([https://junit.org/junit5/](https://docs.scala-lang.org/pt-br/tour/tour-of-scala.html)')
- [Python]([https://rest-assured.io/](https://www.python.org/)')
- [Spark]([https://swagger.io/specification/](https://spark.apache.org/)')
- [Databricks]([https://json-schema.org/](https://www.databricks.com/)')

## Imagens  do projeto
Servicos utilizados da Azure
<h1 align="center">
  <img src="/servicos azure.PNG">
</h1>

Datalakes
<h1 align="center">
  <img src="/Datalakes.PNG">
</h1>

Montando Acesso aos dados
<h1 align="center">
  <img src="/montando_acesso_aos_dados.PNG">
</h1>

Convertendo dados da camada inbound to bronze
<h1 align="center">
  <img src="/inbound_to_bronze.PNG">
</h1>

Convertendo dados da camada bronze to silver
<h1 align="center">
  <img src="/bronze_to_silver.PNG">
</h1>

Pipelines
<h1 align="center">
  <img src="/pipelines.PNG">
</h1>

Gatilho de pipeline
<h1 align="center">
  <img src="/gatilho de pipeline.PNG">
</h1>

workflows Databricks
<h1 align="center">
  <img src="/workflows databricks.PNG">
</h1>

## 📦 Como baixar o projeto e executar a aplicação

```bash

  #Clonar o repositório
  $git clone https://github.com/limaantonio/pipilene-databricks-azure

```

## ![favicon-16x16](https://github.com/heroku/favicon/raw/master/favicon.iconset/icon_16x16.png) API



Desenvolvido por Antonio Carlos
