# OnebiteFlix

## 📌 Sobre o Projeto
OnebiteFlix é uma plataforma de streaming de cursos online, permitindo que usuários explorem, assistam e organizem conteúdos educacionais. O projeto visa proporcionar uma experiência intuitiva para aprendizado, além de oferecer ferramentas administrativas para gerenciamento de cursos.

## 🚀 Funcionalidades
### Para Usuários:
- 🔎 **Pesquisa e Navegação**: Filtragem e busca por cursos.
- 🆕 **Lançamentos**: Acompanhamento de novos cursos.
- ⭐ **Cursos Populares**: Exibição dos cursos mais assistidos e bem avaliados.
- 📋 **Minha Lista**: Adição e remoção de cursos para assistir depois.
- ▶️ **Continuar Assistindo**: Retomar cursos de onde parou.
- 🔑 **Cadastro e Login**: Criar conta, acessar perfis personalizados.

### Para Administradores:
- 📌 **Gerenciamento de Cursos e Episódios**: Criar, editar e remover cursos.
- 🏷️ **Gerenciamento de Categorias**: Criar e organizar cursos por categorias.
- 🎯 **Destaques**: Definir cursos e categorias prioritárias na plataforma.

## 🛠️ Tecnologias Utilizadas
### 🔹 Backend
- Node.js
- NestJS
- PostgreSQL
- JWT para autenticação

### 🔹 Frontend
- React / Next.js
- Tailwind CSS
- TypeScript

### 🔹 Infraestrutura
- Docker
- WebSockets para atualização em tempo real
- Armazenamento de vídeos via serviço de streaming

## 📂 Estrutura do Projeto
```
📦 OnebiteFlix
 ┣ 📂 backend
 ┃ ┣ 📜 server.ts
 ┃ ┣ 📂 src
 ┃ ┃ ┣ 📂 modules
 ┃ ┃ ┃ ┣ 📂 courses
 ┃ ┃ ┃ ┣ 📂 users
 ┃ ┃ ┃ ┗ 📂 auth
 ┣ 📂 frontend
 ┃ ┣ 📜 index.tsx
 ┃ ┣ 📂 components
 ┃ ┣ 📂 pages
 ┣ 📜 README.md
```

## 🎯 Como Executar o Projeto
### 🔧 Pré-requisitos
- Node.js instalado
- Docker configurado (para banco de dados)

### 🏃‍♂️ Rodando o Backend
```bash
cd backend
npm install
npm run start
```

### 🏃‍♂️ Rodando o Frontend
```bash
cd frontend
npm install
npm run dev
```

## 🔐 Autenticação
- O sistema utiliza JWT para segurança.
- Perfis de usuários e administradores.

## 📌 Contribuição
1. Faça um **fork** do projeto.
2. Crie uma **branch** para sua feature (`git checkout -b minha-feature`).
3. Faça **commit** das mudanças (`git commit -m 'Adicionando minha feature'`).
4. Faça o **push** para a branch (`git push origin minha-feature`).
5. Abra um **Pull Request**.

## 📄 Licença
Este projeto está sob a licença MIT.

---
Projeto desenvolvido para aprendizado e aprimoramento de habilidades em desenvolvimento de software. 🚀