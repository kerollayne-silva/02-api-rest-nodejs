# 💸 API de Transações (Node.js + TypeScript)

Este projeto foi desenvolvido como parte dos meus estudos em desenvolvimento backend, através da plataforma da Rocketseat 🚀.

O objetivo principal é a construção de uma API REST utilizando Node.js, com foco em boas práticas, organização de código e introdução ao uso de TypeScript no backend.

---

## 📚 Sobre o projeto

A aplicação simula um sistema simples de controle financeiro, onde é possível:

* Criar transações
* Listar todas as transações
* Visualizar uma transação específica
* Obter um resumo do saldo

Cada transação pode ser do tipo **crédito** ou **débito**, permitindo o cálculo do saldo total.

---

## 🛠️ Tecnologias utilizadas

* Node.js
* TypeScript
* Fastify
* Knex.js
* SQLite
* Zod
* Vitest

---

## ⚙️ Funcionalidades

### 📌 Requisitos Funcionais (RF)

* [x] Criar uma nova transação
* [x] Listar todas as transações
* [x] Visualizar uma transação específica
* [x] Obter o resumo do saldo

---

### 📌 Regras de Negócio (RN)

* [x] A transação pode ser do tipo **crédito** ou **débito**
* [x] O valor deve ser armazenado como positivo (crédito) ou negativo (débito)
* [x] Cada usuário é identificado por um **session_id**
* [x] O usuário só pode visualizar transações que ele criou

---

## 🚀 Como executar o projeto

### 🔧 Instalação

```bash
npm install
```

---

### ▶️ Rodando em desenvolvimento

```bash
npm run dev
```

---

### 🏗️ Build da aplicação

```bash
npm run build
```

---

### ▶️ Rodando versão de produção

```bash
node build/server.js
```

---

## 🧪 Testes

```bash
npm run test
```

---

## 🗄️ Banco de dados

O projeto utiliza SQLite como banco de dados, com controle de versão através de migrations.

Para rodar as migrations:

```bash
npm run knex -- migrate:latest
```

---

## 💡 Aprendizados

Durante o desenvolvimento deste projeto, tive contato com:

* Estruturação de APIs REST
* Uso de TypeScript no backend
* Gerenciamento de banco de dados com Knex
* Criação e uso de migrations
* Validação de dados com Zod
* Testes automatizados com Vitest
* Manipulação de cookies para controle de sessão

---

## ✨ Observação

Este é um projeto de estudo, desenvolvido com o objetivo de aprendizado e prática de conceitos fundamentais de backend.

---
