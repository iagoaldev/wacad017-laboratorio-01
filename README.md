# WACAD017 - Laboratório 01

Primeiro contato com GitHub Actions por meio de um workflow simples.

Este é um repositório independente. O workflow fica em
`.github/workflows/helloFlow.yml`, caminho reconhecido automaticamente pelo
GitHub Actions.

## Exercícios

1. Ativação manual com `workflow_dispatch`.
2. Ativação programada, a cada cinco minutos, com `schedule` e uma expressão
   cron.
3. Ativação por evento com `push`.

Cada configuração é registrada em um commit separado. O histórico do Git
permite consultar as três etapas, enquanto o arquivo atual representa o último
exercício.

## Resultado esperado

O job `first-job` é executado em uma máquina virtual Ubuntu e possui duas
etapas:

```text
Hello World!
Valeu - bye!
```

Toda a criação, os commits, os pushes e a consulta das execuções podem ser
realizados pelo terminal, sem acessar a interface web do GitHub.
