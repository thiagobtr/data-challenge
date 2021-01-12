# data-challenge
Para esse desafio, foram criados os seguintes arquivos:


1. Os dados devem ser carregados em um banco de dados relacional. Preferencialmente deve ser utilizado PostgreSQL ou MySQL. SQLite também pode ser escolhido como alternativa mais simples.

## Descrição dos arquivos

**database.ini** -> arquivo com os dados para conexão do banco de dados
**Dockerfile** -> script com a criação do serviço "app-python" para download dos dados
**docker-compose.yml** -> arquivo com os serviços "db" (PostgreSQL) e app-python (aplicação python)
**requirements.txt** -> arquivo com as bibliotecas necessárias para a execução do script python
**script_download_dados.py** -> script python para download e inclusão dos dados no banco de dados
**script_download_dados_airflow.py** -> versão do script python usando airflow. Indicado para agendamento e monitoramento do script.
**script_SQL.sql** -> script sql com as consultas dos itens 2 e 3.

## Execução
com o docker instalado e os arquivos baixados, execute:
docker-compose up -d

