# Visão Geral do ERP Food Service

## Introdução

O ERP Food Service é um sistema de gestão voltado para estabelecimentos do ramo alimentício.

O projeto também possui finalidade educacional: demonstrar a evolução de uma aplicação desde os fundamentos da linguagem Python até uma arquitetura preparada para ambientes de produção.

## Segmentos atendidos

O sistema deverá evoluir para atender:

- restaurantes;
- lanchonetes;
- pizzarias;
- hamburguerias;
- cafeterias;
- bares;
- delivery;
- estabelecimentos com operação híbrida.

## Objetivo arquitetural

O sistema será desenvolvido progressivamente.

A complexidade arquitetural será introduzida somente quando houver necessidade técnica e conhecimento suficiente para compreender os problemas que cada abordagem resolve.

A evolução planejada inclui conceitos como:

- programação estruturada;
- programação orientada a objetos;
- testes automatizados;
- persistência de dados;
- APIs;
- arquitetura modular;
- multi-tenancy;
- segurança;
- processamento assíncrono;
- comunicação orientada a eventos;
- observabilidade;
- arquitetura distribuída.

## Multi-tenancy

O objetivo final do projeto inclui suporte a múltiplos tenants.

A estrutura conceitual prevista é:

```text
Tenant
└── Empresa
    └── Filiais
        └── Usuários
            └── Dados da operação