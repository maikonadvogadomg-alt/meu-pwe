# ÍNDICE COMPLETO DO PROJETO

> Referência rápida para retomar o projeto a qualquer momento  
> Projeto: PWA/Editor Full-Stack React + Express + PostgreSQL/Neon  
> Atualizado em: 04/05/2026

---

## 1. VISÃO GERAL

Este projeto é uma aplicação web progressiva (PWA) com:
- **frontend** em React + Vite + TypeScript;
- **backend** em Node.js + Express;
- **banco de dados** PostgreSQL com Drizzle ORM;
- **integrações específicas da Replit** para chat, áudio e imagem;
- **páginas utilitárias HTML** em `client/public`;
- **recursos de PWA** como `manifest.json` e `service worker`.

Em linguagem simples:
- o **frontend** é a parte visível;
- o **backend** é o balcão de atendimento;
- o **banco** é o arquivo/depósito;
- as **integrações Replit** são peças terceiras que hoje podem estar amarrando o projeto.

---

## 2. PONTOS DE ENTRADA PRINCIPAIS

### Frontend
- `client/index.html`
  - página base carregada no navegador;
  - injeta `client/src/main.tsx`.

- `client/src/main.tsx`
  - monta o React no elemento `#root`.

- `client/src/App.tsx`
  - componente raiz;
  - organiza as rotas principais da interface.

### Backend
- `server/index.ts`
  - ponto de entrada do servidor Express;
  - registra middleware, sessões, rotas e integração do Vite em desenvolvimento.

### Build/produção
- `script/build.ts`
  - coordena o processo de build da aplicação.

- `server/static.ts`
  - serve os arquivos estáticos em produção.

- `server/vite.ts`
  - integra o Vite ao servidor durante desenvolvimento.

---

## 3. MAPA GERAL DE RELAÇÃO ENTRE AS PARTES