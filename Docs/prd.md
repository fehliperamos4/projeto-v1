Perfeito — vou manter **EXATAMENTE a mesma estrutura do seu PRD**, só adaptando para o prontuário eletrônico 👇

---

# 📄 Product Requirements Document (PRD) - Prontuário Eletrônico

## 1. Visão Geral e Objetivo

O **Prontuário Eletrônico** é uma aplicação web didática que permite o cadastro e gerenciamento de informações de pacientes e seus exames médicos (raio-x, tomografia, exames laboratoriais, etc.).

**O grande diferencial (Regra de Negócio Principal):** O sistema permite que o próprio paciente seja responsável pelo seu prontuário, podendo cadastrar, visualizar e remover seus exames de forma simples e centralizada, enquanto um usuário mestre possui acesso global para auditoria e controle de todos os registros.

---

## 2. Atores do Sistema

* **Visitante:** Usuário não autenticado que acessa a página inicial e deseja se cadastrar como paciente.
* **Paciente:** Usuário autenticado que pode gerenciar seus dados pessoais e exames.
* **Usuário Mestre (Administrador):** Usuário com acesso total ao sistema, podendo visualizar todos os pacientes e seus respectivos exames.

---

## 3. Histórias de Usuário e Escopo

Abaixo estão as funcionalidades principais do MVP (Minimum Viable Product), escritas sob a perspectiva do usuário final.

### 👤 Épico 1: Autenticação e Cadastro

* **US01 - Autocadastro de Paciente:** Como um Visitante, quero preencher um formulário com meus dados pessoais (Nome, CPF, Endereço, Telefone, Senha) para criar meu prontuário eletrônico.

  * *Critérios de Aceitação:* Todos os campos são obrigatórios; o CPF deve ser válido; o paciente deve ser cadastrado com sucesso no sistema.

* **US02 - Acesso ao Sistema (Login):** Como um Paciente, quero inserir meu CPF e Senha para acessar meu prontuário.

---

### 🧪 Épico 2: Gerenciamento de Exames

* **US03 - Cadastrar Exame:** Como um Paciente logado, quero inserir informações sobre meus exames (tipo, descrição, data), para manter meu histórico atualizado.

  * *Critérios de Aceitação:* O tipo de exame deve ser informado (ex: raio-x, tomografia, exame de sangue); todos os campos são obrigatórios; o exame deve ser vinculado ao paciente.

* **US04 - Visualizar Exames:** Como um Paciente, quero visualizar a lista dos exames que cadastrei, para acompanhar meu histórico médico.

  * *Critérios de Aceitação:* A lista deve exibir tipo de exame, data e descrição.

* **US05 - Remover Exame:** Como um Paciente, quero remover exames cadastrados, caso tenha inserido informações incorretas.

  * *Critérios de Aceitação:* O sistema deve permitir a exclusão de exames previamente cadastrados pelo paciente.

---

### 📊 Épico 3: Controle e Administração

* **US06 - Visualizar Pacientes e Exames (Administrador):** Como um Usuário Mestre, quero visualizar todos os pacientes cadastrados e seus respectivos exames, para fins de controle e auditoria.

  * *Critérios de Aceitação:* O sistema deve listar todos os pacientes e permitir a visualização dos exames vinculados a cada um, incluindo informações como tipo, data, quantidade e descrição.
