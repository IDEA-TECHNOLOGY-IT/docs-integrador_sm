# Idea Marketing

## Índice

- [Idea Marketing](#idea-marketing)
  - [Índice](#índice)
  - [Descrição do Projeto](#descrição-do-projeto)
  - [Funcionalidades Principais](#funcionalidades-principais)
  - [Documentação](#documentação)
  - [Considerações Finais](#considerações-finais)

## Descrição do Projeto

O `integrador_sm` é um serviço Python desenvolvido com a Arquitetura Limpa (Clean Architecture) para capturar dados de APIs do Facebook e Instagram e armazená-los em um Data Warehouse (DW) para análise e processamento posterior.

## Funcionalidades Principais

- Conexão com APIs do Facebook e Instagram.
- Captura de dados de redes sociais para análise.
- Integração com múltiplos bancos de dados (MySQL, SQL Server).
- Estrutura modular utilizando padrões de Arquitetura Limpa.
- Sistema automatizado de migração de banco de dados com Alembic.
- Suporte a testes automatizados para garantir a qualidade do código.

## Documentação

Para mais detalhes sobre a configuração, desenvolvimento, migrações e testes, consulte os seguintes documentos:

- [Configuração](configuration.md)
- [Desenvolvimento](development.md)
- [Controle de Migração](migrations.md)
- [Testes Automatizados](testing.md)
- [Contribuição](contributing.md)

## Considerações Finais

Este serviço foi projetado para ser extensível e fácil de manter, utilizando boas práticas de programação e uma arquitetura limpa para garantir a separação de responsabilidades e facilidade de testes. Contribuições são bem-vindas, e o projeto está aberto para melhorias contínuas.
