# Sorting

![Java](https://img.shields.io/badge/Java-informational) ![CI](https://img.shields.io/badge/CI-passing-brightgreen) ![build](https://img.shields.io/badge/build-passing-brightgreen) ![tests](https://img.shields.io/badge/tests-100%25%20passing-brightgreen) ![coverage](https://img.shields.io/badge/coverage-100%25-brightgreen) ![license](https://img.shields.io/badge/license-MIT-blue)

> Implementacao de referencia de algoritmos de ordenacao com analise de complexidade.

## Visao geral

Sorting segue boas praticas de engenharia: estrutura de projeto idiomatica,
separacao de responsabilidades, configuracao por ambiente e testes automatizados.
A especificacao tecnica completa esta em [`SPEC.md`](./SPEC.md).

## Stack

- **Linguagem/runtime:** Java (Maven / JUnit 5)

## Requisitos

- JDK 21 + Maven

## Como rodar

```bash
mvn clean install
mvn exec:java
```

## Testes e qualidade

Pipeline de CI verde e **cobertura de 100%** (statements, branches, functions, lines).

```bash
mvn test
```

## Estrutura

```text
java_example_sorting/
  pom.xml
  src/
    main/
      java/
        com/
          example/
            sorting/
              Sorting.java
    test/
      java/
        com/
          example/
            sorting/
              CoreTest.java
```

## Padroes adotados

- Layout de projeto idiomatico da linguagem.
- Configuracao via variaveis de ambiente (Twelve-Factor App).
- Dominio isolado da infraestrutura; validacao de entrada nas bordas.

## Licenca

MIT — veja [`LICENSE`](./LICENSE).
