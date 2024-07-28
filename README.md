# Análise de Churn de clientes através de uma Pipeline de dados usando Apache Airflow, AWS Glue, S3, Amazon Redshift e Power BI
Neste projeto de engenharia de dados foi feita uma análise de churn de clientes, construí e automatizei um pipeline ETL usando o AWS Glue para carregar dados do bucket AWS S3 em um data Warehouse Amazon Redshift e depois conectar o Power BI ao cluster do Redshift para a visualização do usuário final. O AWS Glue serviu como um rastreador de dados para inferir o esquema do banco de dados depois os dados foram disponibilizados no AWS Athena para extrair os dados através de consultas SQL. O AWS Glue também serviu para carregar os dados rastreados e tratados para o cluster Redshift. O Apache Airflow foi usado para orquestrar e automatizar todo esse processo que era manual.
Diagrama da arquitetura na nuvem AWS:


Data source: https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset?resource=download
