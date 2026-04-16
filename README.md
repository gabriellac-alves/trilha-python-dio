# Sistema Bancário com Programação Orientada a Objetos 🐍🏦

Este projeto foi desenvolvido como parte do desafio de projeto do Bootcamp **Luizalabs - Back-end com Python** na DIO. O objetivo é simular um sistema bancário robusto, aplicando conceitos avançados de POO.

## 🚀 Tecnologias e Conceitos Aplicados
O sistema foi construído utilizando os pilares da POO para garantir um código limpo e escalável:

- **Herança:** Implementada entre as classes `PessoaFisica` e `Cliente`.
- **Encapsulamento:** Uso de propriedades (`@property`) e métodos de classe (`@classmethod`).
- **Abstração:** Criação de uma interface base para transações utilizando a classe abstrata `Transacao` (módulo `abc`).
- **Polimorfismo:** Diferentes tipos de transações (`Saque` e `Deposito`) compartilhando a mesma interface de registro.

## 🛠️ Funcionalidades
- [x] Cadastrar novo usuário (Pessoa Física).
- [x] Criar conta corrente vinculada ao CPF.
- [x] Realizar depósitos e saques com validação de saldo/limite.
- [x] Consultar extrato detalhado com data e hora da transação.
- [x] Limite de 3 saques diários ou R$ 500,00 por operação.
