# Sistema Bancário em Python

Este projeto é um simples **sistema bancário em terminal**, desenvolvido em Python, que permite ao usuário realizar operações básicas como depósito, saque, exibir extrato e encerrar o programa.

## 📋 Funcionalidades

- **Depósito**: Permite adicionar saldo à conta, desde que o valor informado seja positivo.
- **Saque**: Permite retirar saldo, respeitando:
  - Limite de saque por operação (`R$ 500,00`).
  - Limite de quantidade de saques diários (`3 saques`).
  - Saldo disponível na conta.
- **Extrato**: Exibe todas as movimentações realizadas e o saldo atual.
- **Sair**: Encerra o programa.

## 🛠 Tecnologias Utilizadas

- **Python 3**

## 📄 Observações

- 💰 O limite de saque por operação é de **R$ 500,00**.  
- 🔄 É permitido realizar no máximo **3 saques** por sessão.  
- 🚫 Não é permitido depositar ou sacar valores **negativos ou nulos**.
