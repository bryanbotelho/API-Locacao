# 🏡 Sistema de Reservas de Imóveis – API Node.js

API RESTful para gerenciamento de usuários, imóveis e reservas. Desenvolvido com Node.js, Express e Sequelize, utilizando PostgreSQL como banco de dados e suporte a upload de imagens com multer.

---

## 🚀 Tecnologias Utilizadas

- **Node.js**
- **Express**
- **Sequelize ORM**
- **PostgreSQL**
- **Multer (upload de imagens)**
- **JWT (autenticação)**
- **Bcrypt (hash de senhas)**

---

## 📁 Estrutura do Projeto

```
src/
├── app.js
├── server.js
├── routes.js
├── config/
│   └── upload.js
├── controllers/
│   ├── DashboardController.js
│   ├── HouseController.js
│   ├── ReserveController.js
│   └── SessionController.js
├── models/
│   ├── House.js
│   ├── Reserve.js
│   └── User.js
```

---

## ⚙️ Requisitos

- Node.js
- PostgreSQL
- Sequelize CLI
- yarn ou npm

---

## 🔧 Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/seuusuario/nome-do-repositorio.git
cd nome-do-repositorio
```

### 2. Instale as dependências

```bash
npm install
# ou
yarn install
```

### 3. Configure o banco de dados

Atualize o arquivo de conexão com seu banco PostgreSQL (ex: `config/database.js` ou `.env`).

### 4. Execute as migrations

```bash
npx sequelize-cli db:migrate
```

### 5. Inicie o servidor

```bash
node src/server.js
```

Servidor em: [http://localhost:3333](http://localhost:3333)

---

## 📦 Funcionalidades Principais

- 📌 **Cadastro e login de usuários**
- 🏠 **CRUD de imóveis (Houses)**
- 📅 **Sistema de reservas**
- 🧾 **Listagem de reservas por usuário**
- 🖼️ **Upload de imagens de imóveis**

---

## 🔐 Autenticação

A autenticação é feita via **JWT** e protegida por middleware nas rotas privadas.

---

## 🧪 Testando a API

Use o **Insomnia** ou **Postman** para testar as rotas.

Exemplo de headers com token JWT:

```json
Authorization: Bearer seu_token_jwt
```

---

## 📬 Contato

Desenvolvido por **Bryan Botelho**  
[LinkedIn](https://www.linkedin.com/in/bryan-botelho)  
[GitHub](https://github.com/bryanbotelho)

---
