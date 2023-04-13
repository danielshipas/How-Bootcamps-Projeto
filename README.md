
# Proposta do Projeto

## Objetivo do projeto
O objetivo deste projeto é desenvolver um sistema de processamento de dados em tempo real para monitorar e analisar o comportamento do usuário em um aplicativo de comércio eletrônico. O sistema deve ser capaz de coletar e processar dados de forma eficiente e escalável, fornecendo insights em tempo real para melhorar a experiência do usuário e aumentar as vendas.

### Motivação do projeto
O comércio eletrônico está se tornando cada vez mais competitivo e é fundamental para as empresas terem uma compreensão profunda do comportamento do usuário em seus aplicativos. A análise de dados em tempo real pode fornecer insights valiosos sobre como os usuários estão interagindo com o aplicativo, onde estão ocorrendo problemas e como melhorar a experiência do usuário. Com base nessas informações, as empresas podem fazer ajustes rápidos e efetivos para melhorar a conversão e aumentar as vendas.

### Aplicação prática do projeto
Este projeto pode ser aplicado em qualquer empresa que possua um aplicativo de comércio eletrônico. A análise em tempo real do comportamento do usuário pode ser usada para melhorar a experiência do usuário, aumentar as vendas e fidelizar clientes. Além disso, o sistema pode ser usado para detectar e prevenir fraudes em tempo real.

### Resultados esperados
Esperamos que este projeto possa fornecer insights valiosos sobre o comportamento do usuário em um aplicativo de comércio eletrônico, permitindo que as empresas façam ajustes rápidos e efetivos para melhorar a experiência do usuário, aumentar as vendas e fidelizar clientes. Também esperamos que o sistema possa detectar e prevenir fraudes em tempo real, economizando tempo e dinheiro para as empresas.

## Construção do projeto
### Métodos e serviços a serem utilizados
Para construir o sistema de processamento de dados em tempo real, serão utilizados os seguintes métodos:

 Coleta de dados em tempo real usando ferramentas de streaming, como Apache Kafka.
- Armazenamento de dados em um serviço de armazenamento em nuvem, como AWS S3.
- Processamento de dados em tempo real usando o Apache Spark provisionado via Databricks.
- Consultas simples usando o AWS Athena.
- Implantação dos scripts de ingestão usando o serviço AWS Lambda.
- Orquestração de todos os jobs usando o Airflow.
- Produtos ou serviços ou sistemas a serem usados

Os seguintes produtos, serviços ou sistemas serão usados para construir o sistema de processamento de dados em tempo real:

- Apache Kafka para coleta de dados em tempo real.
- AWS S3 para armazenamento de dados em um serviço de armazenamento em nuvem.
- Apache Spark provisionado via Databricks para processamento de dados em tempo real.
- AWS Athena para consultas simples.
- AWS Lambda para implantação dos scripts de ingestão.
- Airflow para orquestração de todos os jobs.
 
 
## Escopo da arquitetura do projeto
A arquitetura do sistema de processamento de dados em tempo real será composta por quatro camadas:


- Camada de coleta de dados: esta camada será responsável pela coleta de dados em tempo real utilizando ferramentas de streaming, como Apache Kafka. Os dados serão coletados a partir do aplicativo de comércio eletrônico, como as ações do usuário, histórico de navegação, transações e outras informações relevantes.

- Camada de armazenamento de dados: nesta camada, os dados coletados serão armazenados em um serviço de armazenamento em nuvem, como AWS S3. Isso permitirá que os dados sejam armazenados de forma eficiente, escalável e segura.

- Camada de processamento de dados: nesta camada, os dados armazenados na camada anterior serão processados em tempo real utilizando o Apache Spark provisionado via Databricks. Isso permitirá a análise em tempo real dos dados coletados e o fornecimento de insights valiosos para melhorar a experiência do usuário e aumentar as vendas.

- Camada de consultas: nesta camada, as consultas simples aos dados serão realizadas usando o AWS Athena. Isso permitirá que as informações sejam acessadas rapidamente e de forma eficiente.

Além disso, a implantação dos scripts de ingestão será feita usando o serviço AWS Lambda e a orquestração de todos os jobs será gerenciada pelo Airflow. Essa arquitetura permitirá a construção de um sistema de processamento de dados em tempo real eficiente, escalável e seguro para monitorar e analisar o comportamento do usuário em um aplicativo de comércio eletrônico.


