# springboot
Exemplo de API RESTful utilizando o Modelo de Maturidade de Richardson
Este projeto é uma implementação de uma API RESTful que segue os princípios do Modelo de Maturidade de Richardson, fornecendo um serviço CRUD (Create, Read, Update, Delete) para gerenciar recursos.

Tecnologias utilizadas

Java 17
Spring Boot
Banco de dados: [PostgreSQL]

Como executar o projeto

Clone o repositório em sua máquina: git clone https://github.com/cors4rio/springboot
Navegue até o diretório raiz do projeto: cd api-restful-richardson-maturity-model
Execute o comando para compilar o projeto: ./mvnw clean package
Execute o comando para rodar a aplicação: java -jar target/api-restful-richardson-maturity-model-0.0.1-SNAPSHOT.jar

Endpoints disponíveis

A API possui os seguintes endpoints:
GET /recursos: Retorna todos os recursos cadastrados.
GET /recursos/{id}: Retorna o recurso com o ID especificado.
POST /recursos: Cria um novo recurso.
PUT /recursos/{id}: Atualiza o recurso com o ID especificado.
DELETE /recursos/{id}: Deleta o recurso com o ID especificado.
