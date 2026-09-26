# Banking OOP 🏦

Simulação de operações bancárias desenvolvida com JavaScript durante minha formação em Desenvolvimento Front-End na Kenzie Academy Brasil, em 2022.

O projeto foi criado para aplicar conceitos de Programação Orientada a Objetos, utilizando classes, herança e métodos estáticos para representar clientes, contas e operações financeiras.

## Funcionalidades

- Cadastro de diferentes tipos de clientes
- Representação de pessoas e empresas
- Controle de saldo
- Transferência entre contas
- Depósito em conta
- Pagamento de salário
- Validação de saldo antes das operações
- Validação de regras específicas de pagamento
- Registro do histórico de transações
- Diferenciação entre pagamentos e recebimentos

## Tecnologias e conceitos

- JavaScript
- Programação Orientada a Objetos
- Classes
- Herança
- `extends`
- `super`
- Métodos estáticos
- `instanceof`
- Arrays e objetos
- Regras de negócio
- Git e GitHub

## Modelagem

A aplicação utiliza uma classe base `Cliente`, responsável pelas informações comuns das contas e pelo histórico de operações.

A partir dela são especializadas duas classes:

- `Pessoa` — representa clientes pessoa física
- `Empresa` — representa clientes pessoa jurídica

As operações financeiras são centralizadas na classe `Transacao`.

## Operações

### Transferência

Realiza transferências entre contas após verificar se a conta de origem possui saldo suficiente.

A operação é registrada no histórico das duas contas como pagamento e recebimento.

### Depósito

Adiciona o valor à conta de destino e registra a operação em seu histórico.

### Pagamento de salário

Realiza o pagamento após validar as regras definidas para a operação, incluindo o tipo de cliente, limite do valor e saldo disponível.

## Contexto

Projeto acadêmico desenvolvido em 2022 durante minha formação em Desenvolvimento Front-End na Kenzie Academy Brasil.

O código foi preservado em seu estado original como parte do meu histórico de aprendizado e evolução em JavaScript e Programação Orientada a Objetos.