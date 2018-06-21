# UFG-INF-ES-DW-2018-1

## Arquivos

`pom.xml` - Arquivo de configuraÃ§Ã£o do projeto Maven.

`src/main/webapp` - Pasta para colocar conteÃºdo web. 

## Para executar o Tomcat

`mvn tomcat7:run`

## Para executar o Derby

`mvn exec:java@derby-start`

## Banco de Dados

### JDBC

URL: `jdbc:derby://localhost:1527/vendadb`

UsuÃ¡rio: `app`

Senha: `app`

### Tabelas

`
CREATE TABLE "user" (
  name VARCHAR(100),
  email VARCHAR(100),
  age INTEGER
)
`
