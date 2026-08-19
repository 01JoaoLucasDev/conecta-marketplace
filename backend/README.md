# Backend

## Descrição

Esta pasta contém todo o código responsável pelo backend do Conecta Marketplace.

O backend será responsável por fornecer a API da aplicação, implementar as regras de negócio, controlar o acesso aos dados, realizar autenticação e autorização dos usuários e disponibilizar os serviços necessários para o frontend e, futuramente, para o aplicativo mobile.

A aplicação backend será desenvolvida utilizando Java e Spring Boot, seguindo uma arquitetura organizada e preparada para evolução.

## Principais responsabilidades

O backend será responsável por:

- Gerenciamento de usuários;
- Cadastro e autenticação;
- Gerenciamento de clientes;
- Gerenciamento de prestadores;
- Cadastro de serviços;
- Cadastro e gerenciamento de habilidades;
- Busca de profissionais;
- Sistema de matching entre clientes e prestadores;
- Solicitação de serviços;
- Envio e gerenciamento de propostas;
- Agendamento de serviços;
- Controle do status dos serviços;
- Sistema de avaliações;
- Sistema de reputação;
- Sistema de mensagens;
- Notificações;
- Denúncias e bloqueios;
- Controle de permissões;
- Integração com serviços externos;
- Futuramente, processamento de pagamentos.

## Estrutura esperada

O backend deverá ser organizado em módulos ou pacotes de acordo com os principais domínios da aplicação.

Exemplos:

- usuários;
- autenticação;
- prestadores;
- clientes;
- serviços;
- habilidades;
- solicitações;
- propostas;
- agendamentos;
- avaliações;
- mensagens;
- notificações.

## Tecnologias

A definição final das tecnologias será documentada durante o desenvolvimento.

Tecnologias inicialmente previstas:

- Java;
- Spring Boot;
- Spring Web;
- Spring Data JPA;
- Spring Security;
- PostgreSQL;
- Maven;
- JWT.

## Objetivo

Construir uma API segura, organizada, testável e escalável, responsável por concentrar as regras de negócio do Conecta Marketplace.