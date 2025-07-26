# 🧮 Calculadora em JavaScript com Funções em Objeto

Este é um projeto básico de uma calculadora implementada em JavaScript, utilizando um objeto que agrupa várias operações matemáticas.

## 📁 Arquivo

- `funcoesObjeto.js`: contém todas as funções da calculadora.

## ⚙️ Funcionalidades

A calculadora oferece as seguintes operações:

- Soma: `calculadora.soma(a, b)`
- Subtração: `calculadora.subtracao(a, b)`
- Multiplicação: `calculadora.multiplicacao(a, b)`
- Divisão (com verificação de divisão por zero): `calculadora.divisao(a, b)`
- Cálculo de média de uma lista de números: `calculadora.calcularMedia([n1, n2, n3, ...])`

## 🧪 Exemplo de uso

```javascript
console.log(calculadora.soma(5, 3)); // 8
console.log(calculadora.divisao(10, 0)); // "Divisão por zero não é permitida."
console.log(calculadora.calcularMedia([10, 8, 6])); // 8
