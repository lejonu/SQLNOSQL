# Conceitos de Bancos de Dados Relacionais e não Relacionais.

Nos modelos de bancos de dados relacionais a modelagem e estrutura dos dados é fundamental para o bom desempenho e para a obtenção de respostas satisfatórias. Já os sistemas NoSQL(Not Only SQL) não precisam de uma estrutura rígida e os documentos de um coleção podem ter estruturas diferentes de acordo com a necessidade. 

Os termos ‘SQL’ e ‘NoSQL’ referem-se essencialmente a como esses  esquemas são definidos. Em um banco de dados relacional, os usuários  usam as instruções SELECT, INSERT e DELETE para adicionar ou atualizar  dados.

## SQL

A linguagem SQL (Structured Query Language) é usada para executar  comandos em bancos de dados relacionais, que são os bancos baseados em  tabelas. Com o SQL, você pode executar vários comandos para criar, alterar,  gerenciar, consultar, dentre outras informações no seu banco de dados. 

## NoSQL

NoSQL *(Not Only SQL)* é o termo utilizado para banco de dados não relacionais de alto desempenho, onde geralmente não é utilizado o  SQL como linguagem de consulta. O NoSQL foi criado para ter uma  performance melhor e uma escalabilidade mais horizontal para suprir  necessidades onde os bancos relacionais não são eficazes. No geral,  temos 4 tipos de bancos de dados NoSQL:

- **Documento** – Os dados são armazenados como  documentos. Os documentos podem ser descritos como dados no formato de  chave-valor, como por exemplo, o padrão JSON. Um exemplo de banco de  dados neste formato é o MongoDB;
- **Colunas** – Os dados são armazenados em linhas  particulares de tabela no disco, podendo suportar várias linhas e  colunas. Também permitem sub-colunas. Um banco de dados dessa família,  por exemplo, é o Cassandra;
- **Grafos** – Os dados são armazenados na forma de grafos (vértices e arestas). O Neo4j é um banco que utiliza grafos;
- **Chave-valor** – Esta família de bancos NoSQL é a que  aguenta mais carga de dados, pois o conceito dele é que um determinado  valor seja acessado através de uma chave identificadora única. Um  exemplo é o banco de dados Riak.