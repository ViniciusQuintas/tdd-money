# TDD MONEY
Este projeto é um sistema simples para manipulação de valores monetários, implementado em TypeScript usando os princípios de Test Driven Development (TDD).

## Estrutura do Projeto
O projeto é composto pelos seguintes arquivos principais:

- **money.ts**: Define a classe `Money`, que representa um valor monetário em uma moeda específica.
- **bank.ts**: Define a classe `Bank`, que gerencia taxas de câmbio entre diferentes moedas.
- **sum.ts**: Define a classe `Sum`, que representa a soma de duas expressões monetárias.
- **expression.ts**: Define uma interface `Expression` que é implementada por `Money` e `Sum`.
- **money.spec.ts**: Contém testes utilizando Jest para validar as funcionalidades do sistema.

## Tecnologias Utilizadas
- TypeScript
- TDD (Test Driven Development)
- Jest


## Como Testar o Projeto
Os testes foram implementados utilizando o Jest. Para rodar todos os testes basta seguir os seguintes comandos:

Clone o repositório:
```
    git clone https://github.com/ViniciusQuintas/tdd-money
    cd tdd-money
```

Instale as dependências:
```
    npm install
```

Execute os testes

```bash
    npm test
```