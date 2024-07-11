# LiterAlura

Literalura é um projeto proposto pelo programa ONE BR Back End com o consumo da API Gutendex. O projeto permite buscar livros, listar livros registrados, listar autores registrados, listar autores vivos em um determinado ano e listar livros em um determinado idioma.

## Descrição

Este projeto foi desenvolvido para gerenciar livros e autores utilizando o framework Spring Boot. Ele permite realizar buscas por livros utilizando a API externa Gutendex, armazenar os livros e autores em um banco de dados PostgreSQL e realizar diversas consultas no banco de dados.

## Tecnologias Utilizadas

- Java 22.0.1
- Spring Boot 3.3.1
- PostgreSQL
- Maven

## Instalação
### Pré-requisitos
- Java 22.0.1 instalado
- PostgreSQL instalado e configurado
- Maven instalado

## Uso

Ao iniciar a aplicação, você verá o menu principal com as seguintes opções:

Escolha o número de sua opção:

1 - Buscar livro pelo título  
2 - Listar livros registrados  
3 - Listar autores registrados  
4 - Listar autores vivos em determinado ano  
5 - Listar livros em determinado idioma  
0 - Sair


## Funcionalidades

- **Buscar livro pelo título:** Permite buscar um livro pelo título utilizando uma API externa e salvá-lo no banco de dados.
- **Listar livros registrados:** Exibe todos os livros registrados no banco de dados.
- **Listar autores registrados:** Exibe todos os autores registrados no banco de dados.
- **Listar autores vivos em determinado ano:** Exibe todos os autores que estavam vivos em um determinado ano.
- **Listar livros em determinado idioma:** Exibe todos os livros registrados no banco de dados em um determinado idioma.

## Exemplo de Uso

Para buscar um livro pelo título:

1. Escolha a opção 1.
2. Digite o título do livro que deseja buscar.
3. O sistema buscará o livro na API externa e o salvará no banco de dados se não estiver registrado.

## Idiomas Suportados

Ao listar livros por idioma, você pode usar os seguintes códigos de idioma:

- **es** - Espanhol
- **en** - Inglês
- **fr** - Francês
- **pt** - Português
