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





