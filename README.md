# CRIANDO UM BANCO E ADICIONANDO DADOS NO SQL SERVER COM PYTHON.

## Oque você encontra em cada pasta:

Pasta 1: GerandoDados
 - Aqui utilizo da biblioteca de Python "Faker" para criar Dados fictícios, usados para inserir no Banco De Dados

   Pasta 1.1: Dados
   - Dados Gerados pela biblioteca Faker

Pasta 2: BancoDeDados
 - Conectando ao servidor SQL.
 - Criação do Banco de Dados.
 - Criação das Tabelas.
 - Inserção dos Dados.


## Observações

Caso queira, para conseguir rodar os códigos, deve criar um servidor no SQL Server/SSMS e alterar as seguintes informações:

![image](https://github.com/user-attachments/assets/9ec92bd6-c098-419a-b870-f36f05c4d400)

Driver: 
Para descobrir qual driver usar, rode o seguinte código no Python
 import pyodbc
 print(pyodbc.drivers())

Deverá retornar os drivers disponíveis, algo como:
 ['SQL Server', 'ODBC Driver 17 for SQL Server']

Server: "Seu Servidor SQL"
