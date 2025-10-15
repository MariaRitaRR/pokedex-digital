# 🧩 Pokédex Digital  

Aplicação full stack desenvolvida com integração à [PokéAPI](https://pokeapi.co/), permitindo listar Pokémon em formato de cards interativos, favoritar criaturas e montar equipes de batalha personalizadas.  

O sistema conta com autenticação de usuários, armazenamento local via SQLite e comunicação entre front-end e back-end para centralizar as funcionalidades.  

---

## 🎯 Objetivo  
Oferecer uma experiência interativa de Pokédex onde o usuário possa:  
- Visualizar Pokémon com filtros por nome e geração;  
- Adicionar Pokémon aos favoritos;  
- Criar uma equipe de batalha com até seis integrantes;  
- Gerenciar seu perfil e autenticação de acesso.

---

## ⚙️ Tecnologias Utilizadas  

### 🐍 Back-End
- **Flask (Python)**  
- **SQLAlchemy (ORM)**  
- **SQLite (Banco de Dados Local)**  
- **Flask-JWT-Extended (Autenticação JWT)**  
- **Requests (Integração com PokéAPI)**  

### 💻 Front-End
- **Angular Framework**  
- **TypeScript**  
- **HTML / CSS / Angular Material**

---

## 🗂 Estrutura do Projeto

```
pokedex-digital/
│
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── models.py
│   │   ├── database.py
│   │   ├── auth.py
│   │   ├── routes/
│   │   │   ├── auth_routes.py
│   │   │   ├── pokemon_routes.py
│   │   │   └── user_routes.py
│   │   ├── controllers/
│   │   │   ├── pokemon_controller.py
│   │   │   └── user_controller.py
│   │   └── utils.py
│   ├── run.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   │   ├── login/
│   │   │   ├── pokedex/
│   │   │   ├── favoritos/
│   │   │   └── batalha/
│   │   └── services/
│   │       └── api.service.ts
│   ├── angular.json
│   └── package.json
│
└── README.md
```

---

## 🔐 Funcionalidades Implementadas  

✅ Cadastro e autenticação de usuários (JWT)  
✅ Integração com a PokéAPI  
✅ Listagem de Pokémon com filtros  
✅ Adição e remoção de favoritos  
✅ Criação de equipe de batalha (até 6 Pokémon)  
✅ Armazenamento local em SQLite  

---

## 🚀 Como Executar o Projeto  

### 1️⃣ Clonar o repositório  
```bash
git https://github.com/MariaRitaRR/pokedex-digital
cd pokedex-digital
```

### 2️⃣ Configurar o Back-End  

```bash
cd backend
python -m venv venv
source venv/bin/activate       # Linux/macOS
venv\Scripts\activate          # Windows

pip install -r requirements.txt
python run.py
```

O servidor Flask será iniciado em:
> 🔗 http://localhost:5000

### 3️⃣ Configurar o Front-End  

```bash
cd frontend
npm install
ng serve
```

O front-end será iniciado em:
> 🔗 http://localhost:4200

---

## 🧠 Endpoints Principais  

### 👥 Usuário  
`POST /user/register` → Cria um novo usuário  
`POST /auth/login` → Retorna token JWT  

### 🔎 Pokémon  
`GET /pokemon/<nome>` → Busca Pokémon na PokéAPI  
`POST /pokemon/favoritar` → Marca ou desmarca Pokémon como favorito  

---

## 🧰 Requisitos Mínimos (Obrigatórios)
- Seguir a modelagem proposta no documento  
- Front-End em **Angular**  
- Back-End em **Flask ou Django (Python)**  
- Banco de Dados **SQLite** com **SQLAlchemy**  
- Integração via **PokéAPI**  
- Autenticação com **Token JWT**

---

## 🧱 Requisitos Opcionais (Diferenciais)
- Docker da API  
- Painel para **RESET de Senha**  
- Acesso para **Gestão de Usuários**  

---

## 👨‍💻 Autor  
**Alexandre Cilani** (Professor orientador do projeto)  

**Desenvolvido por:**  
Maria Rita Raposo Rosa  
📧 mariaritarosar@gmail.com  
💻 [github.com/MariaRitaRosa](https://github.com/MariaRitaRosa)  
🔗 [linkedin.com/in/mariaritaraposo](https://linkedin.com/in/mariaritaraposo)

---
# 🧩 Pokédex Digital  

Aplicação full stack desenvolvida com integração à [PokéAPI](https://pokeapi.co/), permitindo listar Pokémon em formato de cards interativos, favoritar criaturas e montar equipes de batalha personalizadas.  

O sistema conta com autenticação de usuários, armazenamento local via SQLite e comunicação entre front-end e back-end para centralizar as funcionalidades.  

---

## 📅 Prazo de Entrega  
**20/10/2025**

---

## 🎯 Objetivo  
Oferecer uma experiência interativa de Pokédex onde o usuário possa:  
- Visualizar Pokémon com filtros por nome e geração;  
- Adicionar Pokémon aos favoritos;  
- Criar uma equipe de batalha com até seis integrantes;  
- Gerenciar seu perfil e autenticação de acesso.

---

## ⚙️ Tecnologias Utilizadas  

### 🐍 Back-End
- **Flask (Python)**  
- **SQLAlchemy (ORM)**  
- **SQLite (Banco de Dados Local)**  
- **Flask-JWT-Extended (Autenticação JWT)**  
- **Requests (Integração com PokéAPI)**  

### 💻 Front-End
- **Angular Framework**  
- **TypeScript**  
- **HTML / CSS / Angular Material**

---

## 🗂 Estrutura do Projeto

```
pokedex-digital/
│
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── models.py
│   │   ├── database.py
│   │   ├── auth.py
│   │   ├── routes/
│   │   │   ├── auth_routes.py
│   │   │   ├── pokemon_routes.py
│   │   │   └── user_routes.py
│   │   ├── controllers/
│   │   │   ├── pokemon_controller.py
│   │   │   └── user_controller.py
│   │   └── utils.py
│   ├── run.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   │   ├── login/
│   │   │   ├── pokedex/
│   │   │   ├── favoritos/
│   │   │   └── batalha/
│   │   └── services/
│   │       └── api.service.ts
│   ├── angular.json
│   └── package.json
│
└── README.md
```

---

## 🔐 Funcionalidades Implementadas  

✅ Cadastro e autenticação de usuários (JWT)  
✅ Integração com a PokéAPI  
✅ Listagem de Pokémon com filtros  
✅ Adição e remoção de favoritos  
✅ Criação de equipe de batalha (até 6 Pokémon)  
✅ Armazenamento local em SQLite  

---

## 🚀 Como Executar o Projeto  

### 1️⃣ Clonar o repositório  
```bash
git clone https://github.com/seuusuario/pokedex-digital.git
cd pokedex-digital
```

### 2️⃣ Configurar o Back-End  

```bash
cd backend
python -m venv venv
source venv/bin/activate       # Linux/macOS
venv\Scripts\activate          # Windows

pip install -r requirements.txt
python run.py
```

O servidor Flask será iniciado em:
> 🔗 http://localhost:5000

### 3️⃣ Configurar o Front-End  

```bash
cd frontend
npm install
ng serve
```

O front-end será iniciado em:
> 🔗 http://localhost:4200

---

## 🧠 Endpoints Principais  

### 👥 Usuário  
`POST /user/register` → Cria um novo usuário  
`POST /auth/login` → Retorna token JWT  

### 🔎 Pokémon  
`GET /pokemon/<nome>` → Busca Pokémon na PokéAPI  
`POST /pokemon/favoritar` → Marca ou desmarca Pokémon como favorito  

---

## 🧰 Requisitos Mínimos (Obrigatórios)
- Seguir a modelagem proposta no documento  
- Front-End em **Angular**  
- Back-End em **Flask ou Django (Python)**  
- Banco de Dados **SQLite** com **SQLAlchemy**  
- Integração via **PokéAPI**  
- Autenticação com **Token JWT**

---

## 🧱 Requisitos Opcionais (Diferenciais)
- Docker da API  
- Painel para **RESET de Senha**  
- Acesso para **Gestão de Usuários**  

---

## 👨‍💻 Autor  
**Alexandre Cilani** (Professor orientador do projeto)  

**Desenvolvido por:**  
Maria Rita Raposo Rosa  
📧 mariaritarosar@gmail.com  
💻 [github.com/MariaRitaRosa](https://github.com/MariaRitaRosa)  
🔗 [linkedin.com/in/mariaritaraposo](https://linkedin.com/in/mariaritaraposo)

---
