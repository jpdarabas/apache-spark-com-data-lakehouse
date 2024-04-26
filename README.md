# Apache Spark com Delta Lake e Apache Iceberg

## Integrantes:

* João Pedro Darabas: <a href = "https://github.com/jpdarabas"> jpdarabas </a>
* Jorge Antônio: <a href = "https://github.com/JorgeAntonioJr"> JorgeAntonioJr </a>

## Dataset:

* Link para o Dataset: <a href = "https://opendatasus.saude.gov.br/dataset/srag-2021-a-2024/resource/8cb52f73-0184-41d5-8a8f-87d8f415652c?inner_span=True"> Dataset </a>

### Descrição:

* Dados com fim de desenvolver a vigilancia da Síndrome Respiratória Aguda Grave (SRAG) no Brasil.
* Documento original possui 62.980 linhas mas limitamos a 10.000 pra conseguir demonstar em projeto, apresentando 191 colunas.


## Dicionário de dados:

* Link para o Dicionário: <a href = "https://s3.sa-east-1.amazonaws.com/ckan.saude.gov.br/SRAG/pdfs/Dicionario_de_Dados_SRAG_Hospitalizado_19.09.2022.pdf"> Dicionário </a>

### Descrição:

* Ultima vez atualizado em 2022, por isso não apresenta novas colunas.
* Documento tem como finalidade descrever as variáveis exportadas para o banco de dados em DBF.

## Spark:

### Descrição: 

* É uma engine para análise e processamento de dados em larga escala.

#### requisitos: 

* Java instalado no PATH do sistema, ou a variável de ambiente JAVA_HOME apontando pro diretório onde o Java está instalado.

## Para nosso projeto:

* Python 3.8+: <a href = "https://www.python.org/downloads/"> Baixar Python </a>
* Docker desktop: <a href = "https://www.docker.com/products/docker-desktop/"> Baixar Docker </a>

## Observações:

* Nosso dataset apresenta uma unica tabela.
  
## Como inicializar o ambiente virtual:
```pip install virtualenv```

```python -m venv venv```

```venv\Scripts\activate```

```pip install pyspark```

```deactivate```



