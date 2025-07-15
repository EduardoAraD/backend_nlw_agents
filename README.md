# 🚀 Backend NLW Agents

API desenvolvida durante o **Next Level Week (NLW) - Agents** da Rocketseat, responsável pelo gerenciamento de agentes, incluindo criação, listagem, atualização e exclusão de registros, além de servir dados para o frontend do projeto.

## ✨ Funcionalidades

- CRUD de agentes
- Endpoints RESTful claros e objetivos
- Conexão com banco de dados via Drizzle ORM
- Validação de dados de entrada
- CORS configurado para integração com o frontend

## 📁 Estrutura do projeto


## 🛠️ Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Drizzle ORM](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Gemini](https://github.com/googleapis/js-genai)
- [Fastify](https://fastify.dev/)

## 🚀 Como rodar o projeto

```bash
git clone https://github.com/EduardoAraD/backend_nlw_agents.git

npm install #or
yarn
```
Crie um arquivo .env na raiz do projeto com o seguinte conteúdo:
```bash
# HTTP
PORT=

# DATABASE - POSTGRES
DATABASE_URL=

# GEMINI KEY API
GEMINI_API_KEY=
```

Execute as migrations
```bash
npm run db:generate
npm run db:migrate

# Execute o servidor
npm run dev
```

## 👨‍💻 Autor

Desenvolvido por Eduardo Araújo

GitHub: @EduardoAraD  
LinkedIn: [Eduardo Araújo](https://www.linkedin.com/in/eduardo-araujo-code/)


Feito com 💜 durante o NLW Agents da Rocketseat.
