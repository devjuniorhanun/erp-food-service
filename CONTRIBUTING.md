# Guia de Contribuição

Obrigado pelo interesse em contribuir com o ERP Food Service.

Este documento apresenta as convenções iniciais utilizadas no desenvolvimento do projeto.

## Idioma

A documentação deve ser escrita em Português do Brasil (pt-BR).

Nomes utilizados no código-fonte devem seguir as convenções adotadas pelo projeto e, preferencialmente, utilizar inglês.

## Fluxo de desenvolvimento

O projeto utiliza Git Flow.

As branches principais são:

- `main`: contém versões estáveis do projeto;
- `develop`: concentra as funcionalidades destinadas à próxima versão.

O desenvolvimento de novas funcionalidades deve ocorrer em branches `feature/*`.

## Criando uma feature

Uma nova feature deve ser criada a partir da `develop`.

Exemplo:

```bash
git flow feature start product-registration
```

Durante o desenvolvimento, faça commits pequenos e relacionados à alteração realizada.

Após concluir e verificar a feature:

```bash
git flow feature finish product-registration
```

## Commits

O projeto utiliza Conventional Commits.

Exemplos:

```text
feat: add product registration
fix: prevent negative stock
docs: update project documentation
test: add product tests
refactor: extract product validation
chore: update development configuration
```

## Testes

Toda regra de negócio deverá possuir testes quando a estrutura de testes correspondente estiver disponível.

Antes de concluir uma feature, os testes existentes deverão ser executados.

## Documentação

Alterações relevantes no comportamento, arquitetura ou processo de desenvolvimento devem ser acompanhadas pela atualização da documentação correspondente.