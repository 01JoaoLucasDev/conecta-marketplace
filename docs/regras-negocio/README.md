# Regras de Negócio

## Descrição

Esta pasta contém as regras que determinam como o Conecta Marketplace deverá funcionar do ponto de vista do negócio.

As regras de negócio representam condições, restrições e comportamentos que deverão ser respeitados pelo sistema.

## Exemplos

- Um prestador deve possuir pelo menos uma habilidade para oferecer serviços;
- Uma avaliação somente poderá ser realizada após a conclusão de um serviço;
- Um usuário não poderá avaliar a si próprio;
- Um prestador somente poderá receber solicitações dentro da área de atendimento definida;
- Uma solicitação poderá receber múltiplas propostas;
- Uma proposta poderá ser aceita ou recusada pelo cliente;
- Um serviço deverá possuir um status durante seu ciclo de vida.

## Identificação

As regras deverão possuir identificadores únicos.

Exemplo:

RN-001 - Regra de cadastro

RN-002 - Regra de avaliação

RN-003 - Regra de cancelamento

RN-004 - Regra de disponibilidade

## Objetivo

Centralizar as regras que determinam o comportamento da plataforma e garantir que elas sejam respeitadas tanto pelo backend quanto pelas interfaces do sistema.