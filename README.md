# Store Datawarehouse Implementation
## Situação Problématica

Contexto:
Se temo uma base de dados que armazena as informações dos produtos que entraram e saíram de um supermercado, atualmente a gerência reúne com informações em planilhas de excel, as vezes as informações não batem certo
com o que literalmente se te em estoque nas lojas. 
Se gostaria de ter essa informação em D-1 para se poder avaliar a situação do estoque e traçar estratégias de compras com os fornecedores.

# Tecnologias Utilizadas
SQL Server Integration Services (SSIS)

SQL Server 2019

T-SQL 

SQL Arquitect

Visual Studio 2022

# Modelagem do Projecto (Data Warehouse)

A modelagem consiste na ilustração gráfica do funcionamento de qualquer sistema de informação, para facilitar o seu entendido e funcionamento, por parte de quem é alheio ao sistema e ajuda na manuntenção do mesmo para futuras escalabilidade. Para modelagem deste projecto se utilizou o SQL Arquitect.

![Modelling](https://github.com/ffquindala/store_datawarehouse_implentation/assets/80399273/f10c3d48-5828-4c6f-ab91-a3cd8478095a)

# ETL para Stage Are

Staging Area, serve como uma área de preparação (intermediária) antes de armazenar em DW, tem ainda como finalidade proteger o DW de erros nos dados. De forma geral é na SA onde ocorre maior parte das transformações para posteriormente fazer carregamendo em DW.

![Stage Package](https://github.com/ffquindala/store_datawarehouse_implentation/assets/80399273/cb59f7af-9bde-4e1f-8791-eff88747ecb5)


