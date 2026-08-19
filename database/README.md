# Database

## Descrição

Esta pasta contém os arquivos relacionados ao banco de dados do Conecta Marketplace.

O banco de dados será responsável pelo armazenamento e gerenciamento das informações utilizadas pela plataforma.

## Informações armazenadas

Entre os principais dados estão:

- Usuários;
- Clientes;
- Prestadores;
- Serviços;
- Categorias;
- Habilidades;
- Localizações;
- Disponibilidades;
- Solicitações;
- Propostas;
- Agendamentos;
- Avaliações;
- Mensagens;
- Notificações;
- Denúncias;
- Histórico de operações.

## Estrutura

Esta pasta poderá conter:

### Migrations

Arquivos responsáveis pela criação e alteração da estrutura do banco de dados.

### Seeds

Dados iniciais utilizados para desenvolvimento e testes.

### Diagrams

Diagramas relacionados à modelagem do banco.

### Scripts

Scripts SQL auxiliares.

## Modelagem

A modelagem deverá representar adequadamente os relacionamentos entre os principais componentes da plataforma.

Exemplos:

- Um usuário pode possuir um perfil de prestador;
- Um prestador pode possuir várias habilidades;
- Uma solicitação pertence a um cliente;
- Uma solicitação pode receber várias propostas;
- Uma proposta pertence a um prestador;
- Um serviço pode gerar uma avaliação;
- Uma avaliação relaciona um avaliador e um usuário avaliado.

## Banco inicialmente previsto

PostgreSQL.

## Objetivo

Manter a estrutura e evolução do banco de dados organizadas, versionadas e reproduzíveis em diferentes ambientes.