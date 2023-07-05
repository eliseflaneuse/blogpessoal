# Projeto Blog Pessoal


## Diagrama de Classes

O diagrama abaixo representa a estrutura do projeto Blog Pessoal:

<div align="center"><img src="https://i.imgur.com/G71SCJ0.png" title="source: imgur.com" /></div>

O projeto é composto por 3 recursos principais e uma classe auxiliar:

### Postagem

O recurso responsável por definir o objeto `Postagem` (posts) do Blog Pessoal.

### Tema

O recurso responsável por classificar as postagens através do objeto `Tema`.

### Usuario

O recurso responsável por definir o objeto `Usuario`, que poderá acessar e criar postagens no Blog Pessoal.

### UsuarioLogin

Classe auxiliar utilizada para efetuar login no Blog Pessoal.

Cada recurso será mapeado como uma tabela no banco de dados da aplicação. A classe auxiliar não gerará uma tabela no banco de dados, pois ela será utilizada apenas como uma classe auxiliar para a implementação da segurança da aplicação.

## Diagrama de Entidade e Relacionamentos

O diagrama abaixo representa o modelo de entidade e relacionamentos do projeto Blog Pessoal:

<div align="center"><img src="https://i.imgur.com/zmzehFU.png" title="source: imgur.com" /></div>

Antes de começar a criar as classes, vamos configurar o nosso projeto Spring Boot no Spring Initializr dentro do STS e configurar o banco de dados da aplicação.

## Configuração do Projeto Spring Boot

Para iniciar o projeto Spring Boot, siga os passos abaixo:

1. Acesse o Spring Initializr (https://start.spring.io/) no seu navegador.
2. Configure as seguintes opções:
   - Project: Spring Boot
   - Language: Java
   - Spring Boot: (versão desejada)
   - Group: com.generation.blogpessoal
   - Artifact: blogpessoal
   - Packaging: Jar
   - Java: (versão desejada)
   - Dependencies: Spring Web, Spring Data JPA, Spring Boot Dev Tools, Validation, MySQL Driver, Lombok(opcional);
3. Clique no botão "Generate" para baixar o arquivo ZIP contendo o projeto.
4. Importe o projeto ZIP no seu ambiente de desenvolvimento (por exemplo, STS, IntelliJ, etc.).
5. Configure o banco de dados da aplicação de acordo com as necessidades do projeto.


