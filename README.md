# App_Contatos

App Contatos com Auth — Expo + TypeScript + Expo Router
Aplicativo gerenciador de contatos com autenticação, desenvolvido com Expo (React Native, TypeScript e Expo Router) e integrado a uma API Node.js/MongoDB (GridFS).
O que a atividade faz
 * Autenticação: Cadastro e login de usuários com tokens JWT armazenados de forma segura via Expo SecureStore.
 * Proteção de Rotas: Bloqueio de acesso às telas internas para usuários não autenticados.
 * CRUD de Contatos: Listagem, cadastro, edição e exclusão de contatos.
 * Upload de Imagens: Seleção de fotos na galeria do dispositivo e envio via multipart/form-data para o GridFS.
