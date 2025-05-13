
# 🎧 Spotify Copy Project

Este é um projeto full-stack que replica visual e funcionalmente uma interface semelhante ao Spotify, com busca e exibição de artistas e músicas populares, integração com MongoDB e navegação dinâmica entre páginas com React Router.

---

## 🚀 Funcionalidades

- 🎵 Listagem de artistas e músicas via API
- 🔁 Navegação entre páginas com React Router
- ▶️ Tela de player com controle de reprodução
- 🧠 Estrutura modular com componentes reutilizáveis
- 📡 Integração completa com MongoDB Atlas
- 🎯 Separação entre Frontend (Vite + React) e Backend (Node.js + Express)

---

## 🧪 Tecnologias Utilizadas

**Frontend**
- React
- Vite
- React Router DOM
- Axios

**Backend**
- Node.js
- Express
- MongoDB (MongoDB Atlas)
- CORS

---

## 📂 Estrutura de Pastas

```
Spotify-Copy-Project/
├── front-end/
│   ├── src/
│   │   ├── pages/         # Páginas (Home, Artists, Songs, Player, etc.)
│   │   ├── components/    # Componentes reutilizáveis
│   │   └── App.jsx        # Roteamento principal
│   ├── index.html
│   └── vite.config.js
│
├── back-end/
│   └── api/
│       ├── connect.js     # Conexão com MongoDB
│       └── server.js      # Endpoints e servidor Express
```

---

## 🔧 Como Rodar o Projeto

### 1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/Spotify-Copy-Project.git
cd Spotify-Copy-Project
```

### 2. Instale as dependências do back-end:

```bash
cd back-end/api
npm install
node server.js
```

> Servidor rodando em `http://localhost:3001`

### 3. Em outro terminal, rode o front-end:

```bash
cd front-end
npm install
npm run dev
```

> Frontend iniciado em `http://localhost:5173`

---

## 🖼️ Prints do Projeto

### Página inicial
![image](https://github.com/user-attachments/assets/1bec3bcd-8429-483d-9ee3-3c6926dc6259)


### Tela do player
![image](https://github.com/user-attachments/assets/dbb27a52-44f8-46c0-9e0e-718c86d49bfc)



### Outra música tocando
![image](https://github.com/user-attachments/assets/7aa2b4e3-e3a7-45d3-abeb-5bf8e699a01f)


### Página de músicas
![image](https://github.com/user-attachments/assets/e6b85d5b-6736-4034-81dc-d8c76b18456a)


---
