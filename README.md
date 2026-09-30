# App Contatos com Auth — Expo + TypeScript + Expo Router

Gerenciador de contatos com autenticação desenvolvido em Expo (React Native + TypeScript + Expo Router) e conectado a uma API Node.js/MongoDB com GridFS.

## Funcionalidades
- Autenticação com token JWT salvo via Expo SecureStore.
- CRUD completo de contatos.
- Upload e visualização de fotos de contatos via GridFS.

## Como rodar
1. Instale as dependências: `npm install`
2. Configure a URL da API em `lib/api.ts` ou via variável de ambiente.
3. Inicie o projeto: `npx expo start`
