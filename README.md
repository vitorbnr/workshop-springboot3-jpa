# Workshop Spring Boot 3 com JPA 🚀

Este projeto faz parte de um workshop prático para aprendizado e aplicação dos conceitos de Spring Boot 3 e JPA (Java Persistence API). A aplicação consiste em uma API REST para gerenciamento de usuários, incluindo operações CRUD e persistência de dados.

## Tecnologias Utilizadas 💻

- **Java 17**
- **Spring Boot 3**
- **Spring Data JPA**
- **Hibernate**
- **Banco de Dados H2 (testes)**
- **Banco de Dados MySQL/PostgreSQL (produção)**
- **Maven**
  
## Como Executar 🚀
Para executar o projeto localmente, siga os passos abaixo:

Clone o repositório:
 ```bash
git clone https://github.com/vitorbnr/workshop-springboot3-jpa.git
```
Navegue até o diretório do projeto:
```bash
cd workshop-springboot3-jpa
```
Compile e instale as dependências:
```bash
./mvnw clean install
```
Execute o projeto no terminal:
```bash
./mvnw spring-boot:run
```
Caso queira executar o projeto na IDE:

Abra sua IDE de preferência.

Importe o projeto como Maven Project.

Execute a classe principal WorkshopSpringboot3JpaApplication.java.

## Instruções de Uso 📋

Rotas GET
/users → Retorna todos os usuários
/users/{id} → Retorna um usuário pelo ID

Rotas POST
/users → Cadastra um novo usuário

Rotas PUT
/users/{id} → Atualiza um usuário existente

Rotas DELETE
/users/{id} → Remove um usuário

## Visualize o H2 Console
Caso utilize o banco H2, siga os passos abaixo para acessar o console e visualizar os dados:

Certifique-se de que a aplicação está rodando.
Acesse o H2 Console no navegador:
```bash
http://localhost:8080/h2-console
```
Use as credenciais abaixo para login:
JDBC URL: jdbc:h2:mem:testdb
User Name: sa
Password: (deixe em branco)
## Aprendizados 📚
Este projeto foi desenvolvido para reforçar os seguintes conceitos:

Desenvolvimento de APIs RESTful com Spring Boot 3.
Persistência de dados utilizando JPA e Hibernate.
Configuração de banco de dados H2, MySQL e PostgreSQL.
Implementação de operações CRUD e boas práticas no backend.
