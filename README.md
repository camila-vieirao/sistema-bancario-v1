<h1>
    <span>DESAFIO DIO - Bootcamp Python AI Backend Developer</span>
</h1>

## Objetivo
Repositório criado para concluir o desafio proposto pela  [DIO](https://www.dio.me/): **Criando um Sistema Bancário com Python**

O sistema é composto por **três operações básicas**:
- Saque
- Depósito
- Visualização de Extrato

## Como o código Funciona

<h3> Extrato </h3>

Este projeto trabalha com apenas um usuário, sendo que todas as operações realizadas por ele ficam armazenadas na variável `extrato`. 

A operação de extrato lista todos os depósitos e saques realizados na conta, e, por fim, é exibido o `saldo` atual do usuário.

<h3> Depósito </h3>

Para realizar um depósito, o valor inserido deve ser obrigatóriamente maior que zero.

<h3> Saque </h3>

Nesta operação, o limite do valor do saque é armazenado na constante `LIMITE_SAQUE`.

O usuário possui uma quantidade máxima de saques, que fica armazenada na constante `QUANTIDADE_MAXIMA_SAQUE`.

Caso o usuário não tenha o saldo disponível para realizar o saque, não será possível realizar a operação.