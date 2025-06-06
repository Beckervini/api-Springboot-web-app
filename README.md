API Spring Boot Web App
Uma API desenvolvida com Spring Boot, focada em demonstrar práticas de desenvolvimento backend em Java. Este projeto foi realizado como parte de um trabalho acadêmico.

Sobre o projeto
O API Spring Boot Web App é uma aplicação backend que expõe endpoints para cadastro e consulta de vagas, utilizando padrões modernos de desenvolvimento com Spring Boot. Conta com camada de validação, integração com banco de dados via JPA, testes automatizados e uma página inicial simples.

Funcionalidades
CRUD de vagas (criar, listar, atualizar e deletar)

Validação de dados de entrada

Respostas amigáveis de erro

Página inicial acessível via navegador

Estrutura RESTful

Tecnologias Utilizadas
Java 17+

Spring Boot

Spring MVC

Spring Data JPA

Maven

Thymeleaf (para templates HTML)

Testes JUnit

Estrutura do Projeto
src/
└── main/
├── java/
│ └── br/
│ └── com/
│ └── fiap/
│ └── sprint3/
│ ├── controlllers/
│ ├── models/
│ └── repositories/
└── resources/
├── application.properties
└── templates/
└── index.html

controlllers/: Controladores REST e da página inicial

models/: Entidades do domínio (ex: Vaga)

repositories/: Repositórios JPA para persistência dos dados

templates/: Páginas HTML

Como rodar o projeto localmente
Clone o repositório
git clone https://github.com/seuusuario/api-Springboot-web-app.git
cd api-Springboot-web-app

Compile o projeto
./mvnw clean install

Inicie a aplicação
./mvnw spring-boot:run

Acesse pelo navegador em http://localhost:8080 ou utilize ferramentas como Postman para testar a API.

Obs.: Lembre-se de configurar o banco de dados no application.properties conforme sua máquina.

Autor
Vinicius Becker
Projeto desenvolvido para fins acadêmicos.

