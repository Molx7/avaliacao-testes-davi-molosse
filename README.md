# Avaliação de Testes - Davi Molosse

Projeto Java desenvolvido para praticar versionamento com Git/GitHub e testes unitários com JUnit.

## Funcionalidades

- Soma de dois números inteiros
- Divisão de dois números inteiros
- Tratamento de divisão por zero com exceção

## Tecnologias utilizadas

- Java
- JUnit 4
- IntelliJ IDEA
- Git/GitHub

## Como executar os testes

Abra o projeto no IntelliJ IDEA, acesse o arquivo `CalculadoraTest.java` e clique com botão direito → **Run 'CalculadoraTest'** para executar todos os testes.

## Resultados dos testes

| Cenário Testado | Resultado Esperado | Resultado Obtido | Status |
|---|---|---|---|
| Soma 3 + 5 | 8 | 8 | Passou |
| Soma 5 + 0 | 5 | 5 | Passou |
| Divisão 8 / 2 | 4 | 4 | Passou |
| Divisão 10 / 0 | ArithmeticException | Exceção lançada corretamente | Passou |
