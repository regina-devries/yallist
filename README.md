[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=com.rodrigopeleias%3Abookstoremanager&metric=alert_status)](https://sonarcloud.io/dashboard?id=com.rodrigopeleias%3Abookstoremanager) [![Build Status](https://travis-ci.org/rpeleias-training/bookstoremanager_course.svg?branch=master)](https://travis-ci.org/rpeleias-training/bookstoremanager_course)

<h2>Gerenciador da API de livraria</h2>

A proposta deste projeto é oferecer uma API REST para o cadastro dos livros de uma livraria.

O código serviu de base para um curso completo sobre o framework, publicado numa plataforma de cursos em agosto de 2020.

Ao longo do projeto são tratados os temas abaixo:

* Preparação do projeto pelo gerador oficial.
* Modelagem de dados para mapeamento das entidades no banco.
* Configuração da análise de qualidade de código na nuvem e como a ferramenta apoia o time.
* Configuração do serviço de integração contínua.
* Implementação das operações de gerenciamento de usuários, livros, autores e editora.
* Autenticação e autorização com a camada de segurança do framework, com suporte a token.
* Relação de cada operação com o padrão arquitetural REST, explicando os conceitos envolvidos durante a implementação.
* Testes unitários validando as funcionalidades.
* Apresentação do desenvolvimento guiado por testes e de como aplicá-lo na prática.
* Testes de integração com a ferramenta de cliente HTTP.
* Abertura de solicitações de merge e revisão de código na prática, e como isso eleva a qualidade do projeto.
* Publicação do sistema na nuvem.

Para executar no terminal, digite:

```shell script
mvn spring-boot:run 
```

Depois disso, basta abrir o endereço abaixo no navegador para ver o resultado:

```
http://localhost:8080/api/v1/books
```