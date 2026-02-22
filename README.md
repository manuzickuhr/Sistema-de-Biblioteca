# 📚 Sistema de Gerenciamento de Biblioteca

Este projeto é um sistema de biblioteca desenvolvido em Python, com integração ao banco de dados MySQL, voltado ao controle de usuários, livros, empréstimos, devoluções e multas.

O sistema é executado via terminal e possui autenticação com controle de permissões por tipo de usuário.

---

## 🚀 Funcionalidades

### 🔐 Autenticação
- Login com usuário e senha
- Controle de tentativas
- Separação de perfis:
  - Funcionário
  - Cliente

---

### 👨‍💼 Funcionalidades do funcionário
- Cadastrar, editar, excluir e listar clientes
- Cadastrar, editar, excluir e listar funcionários
- Cadastrar, editar, excluir e listar livros
- Realizar empréstimos
- Registrar devoluções

---

### 👤 Funcionalidades do cliente
- Visualizar livros disponíveis
- Visualizar seus empréstimos
- Calcular multas
- Visualizar multas
- Pagar multas

---

### 📚 Controle de livros
- Cadastro de livros
- Controle de quantidade

---

### 🔁 Empréstimos
- Registro de empréstimos
- Registro de devoluções
- Associação do funcionário responsável

---

### 💰 Multas
- Cálculo de multa por atraso
- Consulta de multas do cliente
- Pagamento de multa

---

### 🧾 Validações
- Validação de CPF
- Verificação de dados antes de operações no banco

---

## 🛠 Tecnologias utilizadas

- Python
- MySQL
- Programação Orientada a Objetos

---

## 🗃 Estrutura do projeto

- Arquivo principal com os menus e controle do sistema
- Arquivo `classes.py` com as classes:
  - Cliente
  - Funcionario
  - Livro
  - Emprestimo

---

## ▶️ Execução

1. Configure o banco de dados MySQL.
2. Ajuste as credenciais de conexão no arquivo principal.
3. Execute o sistema:

```bash
python main.py
