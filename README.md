## Fin API - Financeira

### Requisitos 

- Deve ser possível criar uma conta
- Deve ser possível buscar o extrato bancário
- Deve ser possível realizar um depósito
- Deve ser possível realizar um saque 
- Deve ser possível buscar o extrato bancário do cliente por data
- Deve ser possível atualizar dados da conta do cliente
- Deve ser possível obter dados da conta do cliente
- Deve ser possível deletar uma conta

## Regras de Negócio

- Não deve ser possível cadastrar uma conta por CPF já existente
- Não deve ser possível fazer deposito em uma conta não existente
- Não deve ser possível buscar extrato em conta não existente
- Não deve ser possível fazer saque em uma conta não existente
- não deve ser possível excluir conta não existente
- Não deve ser possível fazer saque quando o saldo for insuficiente
