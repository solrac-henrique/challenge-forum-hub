

# 💻 Desafio Forum Hub - Oracle One T6



O projeto de topicos é um forum de duvidas ficticio sobre assuntos de programação. 
O projeto deve possuir a criaçao de topicos, tanto a exclusão dos topicos quanto a editação só poderar ser feita pelo criador.

Projeto contara com um cadastro de usuarios, usando criptografia com token JWT, com data de expiração de 3h para ter acesso as requisições.
Todos os usuarios cadastrados serão salvos no banco de dados com senhas criptografadas em algoritmo HMAC256.

API Rest com Spring-boot e Spring-security.


## ⚙️ Funcionalidades

- [x] Cadastro e autenticação de usuários (login com JWT)
- [x] CRUD de tópicos (criação, listagem, atualização e exclusão)
- [x] Restrição de edição/exclusão apenas ao autor do tópico
- [x] Validação para impedir títulos e mensagens duplicados do mesmo usuário
- [x] Tratamento global de erros e exceções da API
- [x] Senhas de usuários criptografadas com HMAC256


## 🛠 Tecnologias

As seguintes tecnologias foram utilizadas no desenvolvimento da API Rest do projeto:

- **[Java 17](https://www.oracle.com/java)**
- **[Spring Boot 3](https://spring.io/projects/spring-boot)**
- **[Spring-security](https://spring.io/blog/2022/02/21/spring-security-without-the-websecurityconfigureradapter)**
- **[Spring-doc](https://springdoc.org/)**
- **[Maven](https://maven.apache.org)**
- **[PostgreSQL](https://www.postgresql.org/docs/14/datatype-numeric.html)**
- **[Hibernate](https://hibernate.org)**
- **[Lombok](https://projectlombok.org)**
- **[JWT](https://jwt.io/)**

## ▶️ Como executar

1. Clone este repositório:

   git clone https://github.com/solrac-henrique/challenge-forum-hub.git

2. Configure as credenciais do banco de dados PostgreSQL no arquivo `application.properties`.
3. Execute o projeto com Maven:
   ./mvnw spring-boot:run

4. A API estará disponível em `http://localhost:8080`.

### Autor: Carlos Henrique Martins


