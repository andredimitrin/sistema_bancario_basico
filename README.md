# Sistema Bancário Simples
 Este é um sistema bancário simples implementado em Python, com interface de linha de comando. Ele permite que os usuários realizem operações bancárias básicas, como depósitos, saques, verificação do saldo da conta e visualização do histórico de transações.

## Como Executar

1. Clone o repositório ou baixe o arquivo do script Python para o seu computador.

2. Abra um terminal ou prompt de comando e navegue até o diretório onde o script está localizado.

3. Execute o script usando o seguinte comando:

```
python banking_system.py
```

## Funcionalidades
### Menu Principal
O sistema bancário apresenta um menu simples para o usuário com as seguintes opções:

**[d] Depositar:** Permite ao usuário realizar um depósito informando o valor desejado.

**[s] Sacar:** Permite ao usuário sacar dinheiro da conta, com certas condições e limites.

**[e] Extrato:** Exibe o histórico de transações (extrato) mostrando todos os depósitos e saques realizados pelo usuário e o saldo atual da conta.

**[q] Sair:** Encerra o sistema bancário e termina o programa.

### Depósito
Quando o usuário escolhe a opção de depósito, ele pode informar um valor positivo que deseja depositar em sua conta. Se o valor informado for válido (maior que 0), o depósito será adicionado ao saldo da conta, e a transação será registrada no histórico de transações (extrato).

### Saque
Os usuários podem selecionar a opção de saque e informar o valor desejado a ser sacado de sua conta. O sistema valida o saque com base nos seguintes critérios:

+ O usuário deve ter saldo suficiente para realizar o saque.
+ O valor do saque não deve exceder o limite de saque da conta.
+ O número de transações de saque não deve exceder um limite pré-definido (LIMITE_SAQUES).

Se alguma das condições não for atendida, o sistema exibirá uma mensagem de erro indicando o motivo da transação falhada. Caso contrário, o valor do saque será deduzido do saldo da conta, e a transação será registrada no histórico de transações (extrato).

### Histórico de Transações (Extrato)
Ao escolher a opção "Extrato", o sistema exibirá o histórico de transações da conta. Se nenhuma transação tiver sido feita, será informado ao usuário que nenhuma movimentação foi registrada. Caso contrário, será exibida uma lista de todos os depósitos e saques realizados pelo usuário, juntamente com o saldo atual da conta.

### Sair do Programa
Ao selecionar a opção "Sair", o sistema bancário será encerrado, e o programa será finalizado.

## Detalhes de Implementação
O sistema bancário é implementado em Python e utiliza um loop simples while True para apresentar o menu principal repetidamente até que o usuário escolha sair. O saldo da conta (saldo), limite de saque (limite) e histórico de transações (extrato) são armazenados em variáveis.

O sistema impõe regras específicas para transações de depósito e saque, incluindo a validação dos valores informados e a verificação se a conta possui saldo suficiente e se o usuário não excedeu o limite de saque. Se uma transação falhar, uma mensagem de erro apropriada é exibida ao usuário.

## Vídeo de Demonstração
Você pode assistir a um vídeo de demonstração do sistema bancário simples:



https://github.com/andredimitrin/sistema_bancario_basico/assets/82331544/d4ba8129-ba75-49ee-a8ab-6dc2c1d2fb28





