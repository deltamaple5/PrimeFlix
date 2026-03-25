🎬 Movie App - Sua Biblioteca de Filmes
## 📝 Sobre o Projeto
Este projeto é uma plataforma de busca e visualização de detalhes de filmes, consumindo dados em tempo real da API do The Movie DB (TMDB). O objetivo foi colocar em prática conceitos avançados de React, como roteamento dinâmico, consumo de APIs externas e notificações de experiência do usuário (UX).

---

## 🚀 Tecnologias Utilizadas
O projeto foi construído utilizando as seguintes ferramentas:

* React.js - Biblioteca principal.

* React Router Dom - Gerenciamento de rotas e navegação.

* React Toastify - Feedback visual com notificações elegantes.

* Axios - Cliente HTTP para as requisições à API.

* TMDB API - Fonte dos dados de filmes.



## ✨ Funcionalidades

* [x] Listagem de filmes populares na página inicial.

* [x] Página de detalhes com sinopse e nota de cada filme.

* [x] Sistema de "Meus Favoritos" (Salvos no LocalStorage).

* [x] Notificações personalizadas ao adicionar ou remover favoritos (Toastify).

* [x] Roteamento completo para uma Single Page Application (SPA).

* [x] Página de erro 404 customizada.

## 🛠️Como Rodar o Projeto

### 1. Clone o Repositório:
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

### 2. Entre na pasta do projeto pelo CMD:
```bash
cd nome-do-repositorio
```

### 3. Instale as dependências:
```bash
npm install react-toastify
npm install react-router-dom
# ou
yarn install
```

### 4. Inicie o servidor de desenvolvimento:
```bash
npm start
# ou
yarn start
```

### 5. Acesse `http://localhost:3000` no seu navegador.

## 📦 Estrutura de Pastas (Resumo)

```Plaintext
src/
 ├── components/          # Componentes menores (Header, Card, Loading)
 │    ├── Header/
 │    │    ├── index.js
 │    │    └── style.css
 ├── pages/               # Páginas principais da aplicação
 │    ├── Home/           # Listagem de filmes
 │    ├── Filme/          # Detalhes do filme selecionado
 │    ├── Favoritos/      # Filmes salvos no LocalStorage
 │    └── Erro/           # Página 404
 ├── services/            # Configurações de API (Axios + TMDB)
 │    └── api.js
 ├── routes.js            # Configuração do React Router Dom
 ├── App.js               # Componente pai e Provider do Toastify
 ├── index.js             # Renderização principal do React
 └── styles.css           # Estilos globais
```