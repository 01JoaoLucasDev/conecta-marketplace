# Infrastructure

## Descrição

Esta pasta contém os arquivos relacionados à infraestrutura necessária para executar, testar, disponibilizar e manter o Conecta Marketplace.

O objetivo é centralizar configurações que não fazem parte diretamente das regras de negócio da aplicação.

## Principais responsabilidades

A infraestrutura poderá abranger:

- Configuração de ambientes;
- Docker;
- Docker Compose;
- Configuração do banco;
- Configuração do backend;
- Configuração do frontend;
- Servidores;
- Deploy;
- CI/CD;
- Monitoramento;
- Logs;
- Variáveis de ambiente;
- Configurações de produção.

## Ambientes

A aplicação poderá possuir diferentes ambientes:

### Desenvolvimento

Utilizado pelos desenvolvedores durante a implementação.

### Testes

Utilizado para validação automática e testes de integração.

### Homologação

Utilizado para validar uma versão antes da publicação.

### Produção

Ambiente utilizado pelos usuários reais da plataforma.

## Segurança

Informações sensíveis, como senhas, tokens, chaves de API e credenciais, não deverão ser armazenadas diretamente no repositório.

Essas informações deverão ser configuradas por meio de variáveis de ambiente ou mecanismos seguros de gerenciamento de secrets.

## Tecnologias

Possíveis tecnologias:

- Docker;
- Docker Compose;
- GitHub Actions;
- serviços de hospedagem em nuvem;
- ferramentas de monitoramento.

## Objetivo

Facilitar a configuração, execução, implantação e manutenção da aplicação nos diferentes ambientes.