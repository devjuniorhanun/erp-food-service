# ERP Food Service

ERP multi-tenant para gestão de estabelecimentos do ramo alimentício.

## Sobre o projeto

O ERP Food Service é um projeto educacional desenvolvido progressivamente durante o estudo de Python e desenvolvimento profissional de software.

O projeto começa com os fundamentos da linguagem Python e evoluirá gradualmente até a construção de um ERP preparado para ambientes de produção.

## Objetivo

Construir um ERP multi-tenant capaz de atender diferentes tipos de estabelecimentos do segmento de alimentação, incluindo:

- restaurantes;
- lanchonetes;
- pizzarias;
- hamburguerias;
- cafeterias;
- bares;
- operações de delivery;
- operações híbridas.

## Status do projeto

Em desenvolvimento.

Atualmente, o projeto encontra-se na fase de preparação do ambiente e estudo dos fundamentos de Python.

## Tecnologias atuais

Neste estágio do projeto:

- Python;
- Git;
- Git Flow.

Novas tecnologias serão adicionadas conforme a evolução e a necessidade do projeto.

## Estrutura atual

```text
erp-food-service/
├── docs/
│   └── overview.md
├── src/
│   └── main.py
├── tests/
│   └── .gitkeep
├── .gitignore
└── README.md
```

## Preparação do ambiente

### Criar o ambiente virtual

```bash
python3 -m venv .venv
```

### Ativar o ambiente virtual

Em Linux:

```bash
source .venv/bin/activate
```

### Executar a aplicação

```bash
python src/main.py
```

## Testes

A estrutura de testes já está preparada.

Os testes automatizados serão introduzidos progressivamente durante o desenvolvimento do projeto.

## Documentação

A documentação complementar está disponível no diretório:

```text
docs/
```

## Fluxo de desenvolvimento

O projeto utiliza Git Flow.

As principais branches são:

- `main`: versões estáveis;
- `develop`: integração do desenvolvimento;
- `feature/*`: desenvolvimento de novas funcionalidades;
- `release/*`: preparação de versões;
- `hotfix/*`: correções críticas de produção.

## Idioma

A documentação do projeto é escrita em Português do Brasil (pt-BR).

O código-fonte, nomes técnicos, branches e mensagens de commit utilizam inglês quando apropriado.