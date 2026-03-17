# 📄 Product Requirements Document (PRD) - Roubank

## 1. Visão Geral e Objetivo

O Prontuário Eletrônico é uma aplicação web didática que permite o cadastro e gerenciamento básico de pacientes.

O objetivo do sistema é armazenar informações simples de pacientes de forma prática, simulando o funcionamento de um sistema utilizado em clínicas, porém com foco em simplicidade e uso acadêmico.

## 2. Atores do Sistema

- **Usuário:** Pessoa que utiliza o sistema para cadastrar e visualizar pacientes.
- **Sistema:** Responsável por armazenar e exibir os dados dos pacientes.

## 3. Histórias de Usuário e Escopo

Abaixo estão as funcionalidades principais do MVP (Minimum Viable Product), escritas sob a perspectiva do usuário final.

### 👤 Épico 1: Cadastro de Pacientes

- **US01 - Cadastrar Paciente:** Como um usuário, quero preencher um formulário com dados básicos do paciente para registrá-lo no sistema.
  - _Critérios de Aceitação:_ Os campos nome e idade são obrigatórios.O paciente deve ser salvo na base de dados. O cadastro deve aparecer na lista após ser salvo


### 💰 Épico 2: Movimentações Financeiras

- **US03 - Visualização de Saldo:** Como um Cliente logado, quero ver meu saldo total atualizado em destaque no painel principal, para saber quanto dinheiro (ainda) tenho.
- **US04 - Realizar Depósito:** Como um Cliente, quero informar um valor para depositar na minha conta.
  - _Critérios de Aceitação:_ O valor deve ser positivo; o sistema deve cobrar uma **"Taxa de Depósito" (ex: 2% do valor)** e creditar apenas o valor líquido na conta do cliente.
- **US05 - Realizar Saque:** Como um Cliente, quero informar um valor para sacar da minha conta.
  - _Critérios de Aceitação:_ O cliente não pode sacar mais do que o saldo disponível + limite; o sistema deve cobrar uma **"Taxa de Saque" (ex: R$ 5,00 fixos por saque)**, descontando o valor do saque + a taxa do saldo total.

### 📊 Épico 3: Histórico e Transparência

- **US06 - Visualizar Extrato:** Como um Cliente, quero visualizar uma lista (tabela ou cards) com o histórico de todas as minhas transações (depósitos e saques).
  - _Critérios de Aceitação:_ A lista deve mostrar a data, o tipo de transação, o valor bruto e **o valor da taxa cobrada** pelo Roubank, deixando claro o quanto o cliente perdeu na operação.








    Product Requirements Document (PRD) – Prontuário Eletrônico
1. Visão Geral e Objetivo



2. Atores do Sistema

Usuário:


Sistema:


3. Histórias de Usuário e Escopo (MVP)
👤 Épico 1: Cadastro de Pacientes

US01 - Cadastrar Paciente
Como um usuário, quero preencher um formulário com dados básicos do paciente para registrá-lo no sistema.

Critérios de Aceitação:

Os campos nome e idade são obrigatórios

O paciente deve ser salvo na base de dados

O cadastro deve aparecer na lista após ser salvo

📋 Épico 2: Visualização

US02 - Listar Pacientes
Como um usuário, quero visualizar uma lista com todos os pacientes cadastrados.

Critérios de Aceitação:

A lista deve exibir nome e idade

Os dados devem ser carregados da API

A lista deve atualizar automaticamente após cadastro

🗑️ Épico 3: Gerenciamento Simples

US03 - Remover Paciente
Como um usuário, quero excluir um paciente da lista.

Critérios de Aceitação:

Deve existir um botão de remoção

O paciente deve ser removido da API

A lista deve atualizar após exclusão

🔹 Observações (Minimalismo)

Não há login/autenticação

Não há edição de paciente

Não há sistema complexo de histórico

Interface simples (formulário + lista)

Foco em aprendizado e funcionamento básico

🎯 Escopo Final (Resumo)

O sistema deve permitir apenas:

✔ Cadastrar paciente

✔ Listar pacientes

✔ Remover paciente
