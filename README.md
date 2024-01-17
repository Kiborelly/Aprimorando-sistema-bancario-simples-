# Simulador de Banco em Python

Este é um simulador simples de banco em Python que oferece funcionalidades como depósito, saque, criação de conta, listagem de contas e saída do programa.

## Funções

### `menu()`
Exibe uma mensagem de boas-vindas e um menu com opções para várias operações bancárias. Retorna a escolha do usuário.

### `deposito(saldo, extrato)`
Permite ao usuário realizar um depósito na conta bancária, atualizando o saldo e o histórico de transações (extrato).

### `saque(saldo, extrato, limite, quantidade_saque, limite_saque)`
Permite ao usuário realizar um saque da conta bancária, considerando limites no número de saques e o limite diário individual. Atualiza saldo e histórico de transações conforme necessário.

### `gerar_extrato(saldo, extrato)`
Gera e exibe um extrato bancário, incluindo histórico de transações e saldo atual.

### `criar_usuario(lista_usuarios)`
Solicita informações do usuário para criar um novo usuário se o CPF fornecido for único; caso contrário, informa ao usuário que o usuário já existe.

### `criar_conta(lista_contas, agencia, lista_usuarios, quantidade_contas)`
Associa uma conta a um usuário existente com base no CPF. Gera um número de conta e adiciona à lista de contas.

### `verificar_cpf(cpf, lista_usuarios)`
Verifica se um CPF dado existe na lista de usuários.

### `main()`
Controla o fluxo principal do programa. O usuário é apresentado a um menu e, com base na escolha, várias funções são chamadas para realizar operações bancárias.

Este código exemplifica conceitos fundamentais de Python, incluindo loops, condicionais, listas, entrada do usuário e uso de funções. Oferece uma aplicação prática para quem está aprendendo programação em Python.