# SISTEMA BANCÁRIO

## Estrutura de Dados

### Contas:

- `nome`
- `CPF` (único)
- `data` data de nascimento (idade > 18)
- `saldo` (começa zerado)
- `extrato` (array de transações)
  - `valor`
  - `data`
  - `descrição`

## Funcionalidades

### Criar Conta

- Informar `nome`, `CPF` e `data` de nascimento

### Pegar Saldo

- Passando `nome` e `CPF`

### Adicionar Saldo

- Passando `nome`, `CPF` e `valor`

### Pegar Conta

- Passando `valor`, `descirção` e `data` de pagamento.
- Caso ele não informe a `data`, considerar pagamento no mesmo dia.
- Não pode haver agendamento para `data` passada.
- Não pode haver pagamento sem que haja `saldo` suficiente.
