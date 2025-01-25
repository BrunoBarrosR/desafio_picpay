# Sistema de Gestão de Produtos com Spring Boot

Este projeto é um **CRUD** (Create, Read, Update, Delete) simples para a gestão de produtos desenvolvido com **Spring Boot**, **JPA** e **H2 Database**. Foi criado com base no vídeo ["CRUD completo com Java Spring Boot, JPA e H2"](https://www.youtube.com/watch?v=dttXo48oXt4&t=9s) do canal **Build & Run**, como parte do meu aprendizado em desenvolvimento backend.

## 🚀 Objetivo do Projeto
Praticar a construção de uma aplicação backend com Spring Boot, incluindo operações de:
- **Criação de produtos**;
- **Leitura de produtos**;
- **Atualização de produtos**;,,,,,,,,
- **Exclusão de produtos**.

## 🛠️ Tecnologias Utilizadas
- **Java 17**: Linguagem de programação principal.
- **Spring Boot**: Framework para criação de aplicações Java.
- **Spring Data JPA**: Abstração para persistência de dados.
- **H2 Database**: Banco de dados em memória para testes e desenvolvimento.
- **Postman**: Testes das APIs REST (opcional).

## 🔧 Como Rodar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
Navegue até o diretório do projeto:

cd nome-do-repositorio
Abra o projeto em sua IDE favorita (ex.: IntelliJ ou Eclipse).

Execute o projeto usando o Maven:

mvn spring-boot:run

Acesse o banco de dados H2 para verificar os dados persistidos:

URL: http://localhost:8080/h2-console
Driver Class: org.h2.Driver
JDBC URL: jdbc:h2:mem:testdb
Usuário: sa
Senha: (deixe em branco)
Teste os endpoints REST:



🌱 Funcionalidades Implementadas
 Operações CRUD de produtos.
 Banco de dados H2 em memória para desenvolvimento e testes.
 Validação de dados no backend.
📚 Referência
Este projeto foi baseado no tutorial:
"CRUD completo com Java Spring Boot, JPA e H2" do canal DevSuperior.

🤝 Contribuição
Este projeto faz parte do meu portfólio e foi desenvolvido para fins educacionais. Feedbacks e sugestões são sempre bem-vindos!
