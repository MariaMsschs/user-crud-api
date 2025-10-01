## Descrição

API em Node.js usando **Express**, **Handlebars** e **Sequelize** para realizar um CRUD de usuários e endereços

---

## Tecnologias utilizadas

* Node.js
* Express
* Express-Handlebars
* Sequelize
* Nodemon (para desenvolvimento)

---

## Estrutura básica

```
index.js              # Entrada principal
db/conn.js            # Conexão com o banco 
models/User.js        # Modelo de usuário
models/Address.js     # Modelo de endereço
views/                # Templates Handlebars
public/css/styles.css # Arquivo de estilos
```

---

## Banco de dados

Certifique-se de atualizar as credenciais de usuário e senha no arquivo `db/conn.js`.

---

## Instalação e execução

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
```

2. Instale as dependências:

```bash
npm install
```

3. Configure a conexão com o banco em `db/conn.js`.

4. Inicie o projeto em modo desenvolvimento:

```bash
npm run dev
```

5. Abra o navegador no endereço padrão:

```
http://localhost:3000
```

> Durante o desenvolvimento, o **nodemon** reinicia o servidor automaticamente ao salvar alterações.

---

## Rotas principais

* `/` → Lista de usuários
* `/users/create` → Formulário para adicionar usuário
* `/users/:id` → Detalhes de um usuário
* `/users/edit/:id` → Edição de usuário
---
