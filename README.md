
# Máquina de Vendas

> Simulação de uma máquina de vendas automática desenvolvida em C.

## Descrição
Este projeto implementa uma máquina de vendas (vending machine) simples, onde o usuário pode inserir saldo, visualizar produtos disponíveis, comprar produtos e acompanhar o estoque. O sistema é totalmente interativo via terminal.

## Funcionalidades
- Inserção de saldo com diferentes valores de notas
- Exibição de produtos disponíveis, preços e estoque
- Compra de produtos com desconto automático do saldo e do estoque
- Controle de estoque em tempo real
- Compatibilidade com Windows e Linux (limpeza de tela adaptativa)

## Estrutura do Código
- **Produto**: Estrutura que armazena nome, preço e estoque de cada item
- **Funções principais**:
	- `inserirSaldo`: Permite ao usuário inserir saldo na máquina
	- `exibirProdutos`: Mostra os produtos disponíveis, preços e estoque
	- `vender`: Realiza a venda, descontando saldo e estoque
	- `main`: Gerencia o fluxo principal do programa

## Exemplo de Uso
1. Ao iniciar, o usuário pode inserir saldo escolhendo entre notas disponíveis
2. O saldo é exibido e os produtos aparecem listados com preço e estoque
3. O usuário escolhe o produto desejado (ou sai)
4. O saldo e o estoque são atualizados automaticamente

## Como compilar
Requer GCC instalado:

```bash
gcc vendas.c -o vendas
```

## Como executar
Após compilar:

```bash
./vendas
```

## Requisitos
- GCC ou compilador C compatível
- Terminal Linux ou Windows

## Produtos disponíveis (padrão)
- Refrigerante: R$6,00 (10 unidades)
- Chocolate: R$4,00 (20 unidades)
- Salgadinho: R$5,00 (10 unidades)
- Suco: R$6,00 (8 unidades)

## Exemplo de execução

```
=== Máquina de Vendas Dionisio ===
Saldo R$10.00

1. Refrigerante	- R$6.00 (Em estoque: 10)
2. Chocolate	- R$4.00 (Em estoque: 20)
3. Salgadinho	- R$5.00 (Em estoque: 10)
4. Suco	- R$6.00 (Em estoque: 8)

0. Sair
Escolha uma opção: 2
```
