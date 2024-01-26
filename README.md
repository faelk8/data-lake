<h1 align="center">
  <img src="image/aws.png" alt="aws" width=360px height=240px >
  <br>
  Data Lake
</h1>

<div align="center">

[![Status](https://img.shields.io/badge/version-1.0-blue)]()
![Static Badge](https://img.shields.io/badge/status-desenvolvimento-deve)
</div>


# Data Lake

Exemplo de como enviar dados para um bucket S3.<br>
Foi coletado dados do site [Govern de Boston](https://data.boston.gov/dataset/311-service-requests) referente aos serviços prestados, os dados foram baixados no formato csv e convertidos para o formato parquet, neste formato ocupa bem menos espaço, em seguida foi enviado para o S3 utilizando boto3.


# S3 
Na AWS foi criado um bucket para inserir os dados.

# Data Lake Formation
Configurado com regras de acesso, caminho para bucket e database.
