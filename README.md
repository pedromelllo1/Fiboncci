# Sequência de Fibonacci

Programa de console em C# que pergunta quantos valores mostrar e imprime a sequência de Fibonacci, começando em 0.

```
Quantos valores: 8
Sequência de Fibonacci com 8 valores
0, 1, 1, 2, 3, 5, 8, 13
```

## Como funciona

Cada número é a soma dos dois anteriores. O programa guarda os dois últimos valores (`a` e `b`) e, a cada volta do laço, mostra `a` e avança: o novo `a` passa a ser o antigo `b`, e o novo `b` passa a ser a soma dos dois.

## Como rodar

O projeto é para .NET Framework 4.7.2.

1. Abra `Fiboncci.sln` no Visual Studio.
2. Rode com **F5** (ou **Ctrl+F5**).
3. Digite quantos valores quer ver e tecle Enter.
