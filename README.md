## Atividade ORM a partir de modelo de dado existente / parte 2

Considerando o arquivo de dados disponibilizado em formato .csv (people-10000.xsl). Faça o que se pede:
A) Crie um novo schema de banco de dados para recepcionar os dados que serão migrados por este trabalho. 
B) Defina uma classe Model do framework ORM (Sequelize) para mapear os dados que estão no arquivo. Todas as colunas são relevantes e devem ser importadas.
C) A tabela que representará o Model deve ser criada pela aplicação (.sync), e não diretamente no banco de dados.
D) Implemente uma funcionalidade que realiza a leitura dos dados do arquivo .csv e fazer a inserção dos registros (um registro por linha) na tabela correspondente no MySQL. A inserção dos dados deve ser feita pelo framework de ORM (Sequelize), e não com raw SQL / native SQL.
E) Após a importação dos dados possibilite o usuário executar duas operações:
1) exibir os dados importados, realizando a leitura dos mesmos diretamente na tabela do MySQL onde os mesmos foram armazenados.
2) Filtrar os dados por nome, onde o usuário poderá entrar com parte de um nome, e a aplicação irá filtrar todos os registros que atendam ao critério LIKE %...% com o termo digitado.

---

## ORM activity from an existing data model / part 2

Consider the data file provided in .csv format (people-10000.xsl). Do the following:
A) Create a new database schema to receive the data that will be migrated by this work. 
B) Define a Model class from the ORM framework (Sequelize) to map the data in the file. All the columns are relevant and must be imported.
C) The table that will represent the Model must be created by the application (.sync), and not directly in the database.
D) Implement a function that reads the data from the .csv file and inserts the records (one record per line) into the corresponding table in MySQL. Data insertion should be done using the ORM (Sequelize) framework, not raw SQL / native SQL.
E) After importing the data, allow the user to perform two operations:
1) display the imported data by scanning it directly into the MySQL table where it was stored.
2) Filter the data by name, where the user can enter part of a name, and the application will filter all the records that meet the LIKE %...% criterion with the term entered.
