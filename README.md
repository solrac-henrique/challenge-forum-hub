

# 💻 Desafio Forum Hub - Oracle One T6



Projeto de fórum de dúvidas fictício sobre assuntos de programação, desenvolvido como desafio final do Programa Oracle One (Alura + Oracle).

A aplicação permite a criação de tópicos, sendo que tanto a edição quanto a exclusão só podem ser realizadas pelo usuário que criou o tópico.

O sistema possui cadastro de usuários com autenticação via token JWT (expiração de 3h por sessão) e senhas armazenadas com criptografia HMAC256. A API segue o padrão REST, construída com Spring Boot e Spring Security.


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


