# PLANO DO PROJETO: HTML/CSS/JS

> Gerado automaticamente pelo SK Code Editor em 02/05/2026, 13:16:56
> **116 arquivo(s)** | **~14.021 linhas de codigo**

---

## RESUMO EXECUTIVO

- **Tipo de aplicacao:** Full-Stack (React + Express)
- **Frontend / Stack principal:** React + Vite, TypeScript, Tailwind CSS, Python
- **Backend / Dados:** Node.js + Express, PostgreSQL, Drizzle ORM
- **Versao:** 1.0.0

**Para rodar o projeto:**
```bash
npm install && npm run dev
```

---

## ESTRUTURA DE ARQUIVOS

```
HTML/CSS/JS/
├── client/
│   ├── public/
│   │   ├── auditoria.html
│   │   ├── codigo-formatacao.txt
│   │   ├── comparador.html
│   │   ├── favicon.png
│   │   ├── manifest.json
│   │   └── sw.js
│   ├── replit_integrations/
│   │   └── audio/
│   │       ├── audio-playback-worklet.js
│   │       ├── audio-utils.ts
│   │       ├── index.ts
│   │       ├── useAudioPlayback.ts
│   │       ├── useVoiceRecorder.ts
│   │       └── useVoiceStream.ts
│   ├── src/
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   │   ├── accordion.tsx
│   │   │   │   ├── alert-dialog.tsx
│   │   │   │   ├── alert.tsx
│   │   │   │   ├── aspect-ratio.tsx
│   │   │   │   ├── avatar.tsx
│   │   │   │   ├── badge.tsx
│   │   │   │   ├── breadcrumb.tsx
│   │   │   │   ├── button.tsx
│   │   │   │   ├── calendar.tsx
│   │   │   │   ├── card.tsx
│   │   │   │   ├── carousel.tsx
│   │   │   │   ├── chart.tsx
│   │   │   │   ├── checkbox.tsx
│   │   │   │   ├── collapsible.tsx
│   │   │   │   ├── command.tsx
│   │   │   │   ├── context-menu.tsx
│   │   │   │   ├── dialog.tsx
│   │   │   │   ├── drawer.tsx
│   │   │   │   ├── dropdown-menu.tsx
│   │   │   │   ├── form.tsx
│   │   │   │   ├── hover-card.tsx
│   │   │   │   ├── input-otp.tsx
│   │   │   │   ├── input.tsx
│   │   │   │   ├── label.tsx
│   │   │   │   ├── menubar.tsx
│   │   │   │   ├── navigation-menu.tsx
│   │   │   │   ├── pagination.tsx
│   │   │   │   ├── popover.tsx
│   │   │   │   ├── progress.tsx
│   │   │   │   ├── radio-group.tsx
│   │   │   │   ├── resizable.tsx
│   │   │   │   ├── scroll-area.tsx
│   │   │   │   ├── select.tsx
│   │   │   │   ├── separator.tsx
│   │   │   │   ├── sheet.tsx
│   │   │   │   ├── sidebar.tsx
│   │   │   │   ├── skeleton.tsx
│   │   │   │   ├── slider.tsx
│   │   │   │   ├── switch.tsx
│   │   │   │   ├── table.tsx
│   │   │   │   ├── tabs.tsx
│   │   │   │   ├── textarea.tsx
│   │   │   │   ├── toast.tsx
│   │   │   │   ├── toaster.tsx
│   │   │   │   ├── toggle-group.tsx
│   │   │   │   ├── toggle.tsx
│   │   │   │   └── tooltip.tsx
│   │   │   ├── pwa-install.tsx
│   │   │   ├── theme-provider.tsx
│   │   │   └── theme-toggle.tsx
│   │   ├── hooks/
│   │   │   ├── use-mobile.tsx
│   │   │   └── use-toast.ts
│   │   ├── lib/
│   │   │   ├── queryClient.ts
│   │   │   └── utils.ts
│   │   ├── pages/
│   │   │   ├── auditoria-financeira.tsx
│   │   │   ├── comparador-juridico.tsx
│   │   │   ├── consulta-corporativo.tsx
│   │   │   ├── consulta-pdpj.tsx
│   │   │   ├── consulta-processual.tsx
│   │   │   ├── login.tsx
│   │   │   ├── not-found.tsx
│   │   │   ├── painel-processos.tsx
│   │   │   ├── playground.tsx
│   │   │   └── token-generator.tsx
│   │   ├── App.tsx
│   │   ├── index.css
│   │   └── main.tsx
│   └── index.html
├── dist/
│   └── public/
│       ├── auditoria.html
│       ├── comparador.html
│       ├── favicon.png
│       ├── index.html
│       ├── manifest.json
│       └── sw.js
├── public/
│   └── auditoria.html
├── script/
│   └── build.ts
├── server/
│   ├── replit_integrations/
│   │   ├── audio/
│   │   │   ├── client.ts
│   │   │   ├── index.ts
│   │   │   └── routes.ts
│   │   ├── batch/
│   │   │   ├── index.ts
│   │   │   └── utils.ts
│   │   ├── chat/
│   │   │   ├── index.ts
│   │   │   ├── routes.ts
│   │   │   └── storage.ts
│   │   └── image/
│   │       ├── client.ts
│   │       ├── index.ts
│   │       └── routes.ts
│   ├── index.ts
│   ├── static.ts
│   ├── storage.ts
│   └── vite.ts
├── shared/
│   ├── models/
│   │   └── chat.ts
│   └── schema.ts
├── components.json
├── drizzle.config.ts
├── fix_buttons.txt
├── main.py
├── package.json
├── postcss.config.js
├── replit.md
├── SISTEMA.md
├── tailwind.config.ts
├── tsconfig.json
└── vite.config.ts
```

---

## STACK TECNOLOGICO DETECTADO

- **Frontend:** React + Vite, TypeScript, Tailwind CSS, Python
- **Backend:** Node.js + Express, PostgreSQL, Drizzle ORM
- **Todos os pacotes (102):** @google/genai, @hookform/resolvers, @jridgewell/trace-mapping, @radix-ui/react-accordion, @radix-ui/react-alert-dialog, @radix-ui/react-aspect-ratio, @radix-ui/react-avatar, @radix-ui/react-checkbox, @radix-ui/react-collapsible, @radix-ui/react-context-menu, @radix-ui/react-dialog, @radix-ui/react-dropdown-menu, @radix-ui/react-hover-card, @radix-ui/react-label, @radix-ui/react-menubar, @radix-ui/react-navigation-menu, @radix-ui/react-popover, @radix-ui/react-progress, @radix-ui/react-radio-group, @radix-ui/react-scroll-area, @radix-ui/react-select, @radix-ui/react-separator, @radix-ui/react-slider, @radix-ui/react-slot, @radix-ui/react-switch, @radix-ui/react-tabs, @radix-ui/react-toast, @radix-ui/react-toggle, @radix-ui/react-toggle-group, @radix-ui/react-tooltip, @tanstack/react-query, @tinymce/tinymce-react, @types/jsonwebtoken, @types/multer, adm-zip, class-variance-authority, clsx, cmdk, connect-pg-simple, date-fns, docx, drizzle-orm, drizzle-zod, embla-carousel-react, express, express-session, framer-motion, html-entities, input-otp, jsonwebtoken, lucide-react, mammoth, memorystore, multer, next-themes, openai, p-limit, p-retry, passport, passport-local, pdf-parse, pg, react, react-day-picker, react-dom, react-hook-form, react-icons, react-resizable-panels, recharts, tailwind-merge, tailwindcss-animate, tinymce, tinymce-i18n, tw-animate-css, vaul, wouter, ws, zod, zod-validation-error, @replit/vite-plugin-cartographer, @replit/vite-plugin-dev-banner, @replit/vite-plugin-runtime-error-modal, @tailwindcss/typography, @tailwindcss/vite, @types/connect-pg-simple, @types/express, @types/express-session, @types/node, @types/passport, @types/passport-local, @types/react, @types/react-dom, @types/ws, @vitejs/plugin-react, autoprefixer, drizzle-kit, esbuild, postcss, tailwindcss, tsx, typescript, vite

---

## ROTAS DA API (endpoints detectados automaticamente)

```
GET    /api/conversations  (em server/replit_integrations/audio/routes.ts)
GET    /api/conversations/:id  (em server/replit_integrations/audio/routes.ts)
POST   /api/conversations  (em server/replit_integrations/audio/routes.ts)
DELETE /api/conversations/:id  (em server/replit_integrations/audio/routes.ts)
POST   /api/conversations/:id/messages  (em server/replit_integrations/audio/routes.ts)
GET    /api/conversations  (em server/replit_integrations/chat/routes.ts)
GET    /api/conversations/:id  (em server/replit_integrations/chat/routes.ts)
POST   /api/conversations  (em server/replit_integrations/chat/routes.ts)
DELETE /api/conversations/:id  (em server/replit_integrations/chat/routes.ts)
POST   /api/conversations/:id/messages  (em server/replit_integrations/chat/routes.ts)
POST   /api/generate-image  (em server/replit_integrations/image/routes.ts)
USE    /{*path}  (em server/static.ts)
USE    /{*path}  (em server/vite.ts)
```

---

## SCRIPTS DISPONIVEIS (package.json)

```bash
npm run dev           # NODE_ENV=development tsx server/index.ts
npm run build         # tsx script/build.ts
npm run start         # NODE_ENV=production node dist/index.cjs
npm run check         # tsc
npm run db:push       # drizzle-kit push
```

---

## VARIAVEIS DE AMBIENTE NECESSARIAS

Crie um arquivo `.env` na raiz com estas variaveis:

```env
DATABASE_URL=seu_valor_aqui
SESSION_SECRET=seu_valor_aqui
PORT=seu_valor_aqui
AI_INTEGRATIONS_OPENAI_API_KEY=seu_valor_aqui
AI_INTEGRATIONS_OPENAI_BASE_URL=seu_valor_aqui
REPL_ID=seu_valor_aqui
```

---

## ARQUIVOS PRINCIPAIS

- `client/index.html` — Arquivo principal
- `client/replit_integrations/audio/index.ts` — Arquivo principal
- `client/src/App.tsx` — Componente raiz do frontend
- `client/src/main.tsx` — Arquivo principal
- `dist/public/index.html` — Arquivo principal
- `main.py` — Aplicacao Python principal
- `server/index.ts` — Ponto de entrada do backend
- `server/replit_integrations/audio/index.ts` — Ponto de entrada do backend
- `server/replit_integrations/batch/index.ts` — Ponto de entrada do backend
- `server/replit_integrations/chat/index.ts` — Ponto de entrada do backend

---

## GUIA COMPLETO — O QUE CADA PARTE DO PROJETO FAZ

> Esta secao explica, em linguagem simples, o que e para que serve cada pasta e cada arquivo.

### 📁 Raiz do Projeto (pasta principal)
> Arquivos de configuracao e pontos de entrada ficam aqui.

**`SISTEMA.md`** _(98 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`components.json`** _(20 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`drizzle.config.ts`** _(15 linhas)_
Configuracao do Drizzle ORM — gerencia a conexao e migracao do banco de dados.

**`fix_buttons.txt`** _(64 linhas)_
Arquivo TXT — parte do projeto.

**`main.py`** _(7 linhas)_
Arquivo Python — codigo de logica ou script de automacao.

**`package.json`** _(128 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`postcss.config.js`** _(7 linhas)_
Configuracao do PostCSS, necessaria para o Tailwind processar os estilos.

**`replit.md`** _(135 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`tailwind.config.ts`** _(108 linhas)_
Configuracao do Tailwind CSS — a biblioteca de estilos visuais usada no projeto.

**`tsconfig.json`** _(24 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.ts`** _(41 linhas)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `client/`
> Pasta 'client' — agrupamento de arquivos relacionados.

**`index.html`** _(23 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

---

### 📁 `public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`auditoria.html`** _(35 linhas)_
Arquivo HTML — parte do projeto.

---

### 📁 `script/`
> Pasta 'script' — agrupamento de arquivos relacionados.

**`build.ts`** _(68 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `server/`
> Pasta 'server' — agrupamento de arquivos relacionados.

**`index.ts`** _(129 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

**`static.ts`** _(20 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`storage.ts`** _(237 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vite.ts`** _(59 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `shared/`
> Pasta 'shared' — agrupamento de arquivos relacionados.

**`schema.ts`** _(155 linhas)_
Arquivo de MODELO — define a estrutura dos dados (tabelas, campos, tipos).

---

### 📁 `client/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`auditoria.html`** _(259 linhas)_
Arquivo HTML — parte do projeto.

**`codigo-formatacao.txt`** _(123 linhas)_
Arquivo TXT — parte do projeto.

**`comparador.html`** _(494 linhas)_
Arquivo HTML — parte do projeto.

**`favicon.png`** _(7 linhas)_
Arquivo de imagem.

**`manifest.json`** _(25 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`sw.js`** _(19 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `client/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(92 linhas)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`index.css`** _(360 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(12 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 `dist/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`auditoria.html`** _(33 linhas)_
Arquivo HTML — parte do projeto.

**`comparador.html`** _(494 linhas)_
Arquivo HTML — parte do projeto.

**`favicon.png`** _(7 linhas)_
Arquivo de imagem.

**`index.html`** _(24 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(25 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`sw.js`** _(62 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `shared/models/`
> Modelos de dados — representacao das tabelas do banco de dados.

**`chat.ts`** _(35 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `client/replit_integrations/audio/`
> Pasta 'audio' — agrupamento de arquivos relacionados.

**`audio-playback-worklet.js`** _(113 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`audio-utils.ts`** _(37 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

**`index.ts`** _(46 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

**`useAudioPlayback.ts`** _(106 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de 'audioplayback'.

**`useVoiceRecorder.ts`** _(53 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de 'voicerecorder'.

**`useVoiceStream.ts`** _(92 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de 'voicestream'.

---

### 📁 `client/src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`pwa-install.tsx`** _(86 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`theme-provider.tsx`** _(47 linhas)_
Componente PROVIDER — 'fornece' dados/funcoes para todos os componentes filhos via Context API do React.

**`theme-toggle.tsx`** _(19 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `client/src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-mobile.tsx`** _(20 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(192 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

---

### 📁 `client/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`queryClient.ts`** _(58 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`utils.ts`** _(7 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `client/src/pages/`
> Telas completas do app — cada arquivo aqui e uma pagina navegavel.

**`auditoria-financeira.tsx`** _(25 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`comparador-juridico.tsx`** _(25 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`consulta-corporativo.tsx`** _(479 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`consulta-pdpj.tsx`** _(671 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`consulta-processual.tsx`** _(656 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`login.tsx`** _(100 linhas)_
Componente de LOGIN/AUTENTICACAO — tela de entrada com usuario e senha.

**`not-found.tsx`** _(33 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`painel-processos.tsx`** _(758 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`playground.tsx`** _(823 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`token-generator.tsx`** _(450 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `server/replit_integrations/audio/`
> Pasta 'audio' — agrupamento de arquivos relacionados.

**`client.ts`** _(275 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`index.ts`** _(15 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

**`routes.ts`** _(137 linhas)_
Arquivo de ROTAS — define as URLs/enderecos respondidos pelo servidor.

---

### 📁 `server/replit_integrations/batch/`
> Pasta 'batch' — agrupamento de arquivos relacionados.

**`index.ts`** _(8 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

**`utils.ts`** _(183 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `server/replit_integrations/chat/`
> Pasta 'chat' — agrupamento de arquivos relacionados.

**`index.ts`** _(4 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

**`routes.ts`** _(119 linhas)_
Arquivo de ROTAS — define as URLs/enderecos respondidos pelo servidor.

**`storage.ts`** _(44 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `server/replit_integrations/image/`
> Pasta 'image' — agrupamento de arquivos relacionados.

**`client.ts`** _(60 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`index.ts`** _(4 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

**`routes.ts`** _(32 linhas)_
Arquivo de ROTAS — define as URLs/enderecos respondidos pelo servidor.

---

### 📁 `client/src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(57 linhas)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(140 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(60 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(6 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(52 linhas)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(39 linhas)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(116 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button.tsx`** _(63 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(69 linhas)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(86 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(261 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(366 linhas)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(12 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(152 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(199 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(123 linhas)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(119 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(199 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`form.tsx`** _(179 linhas)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(30 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-otp.tsx`** _(70 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(24 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`label.tsx`** _(25 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(257 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(129 linhas)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(118 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(30 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(43 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(47 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(161 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(30 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(141 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(728 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(16 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`switch.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(118 linhas)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(54 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(23 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(128 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(34 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(62 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(44 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(31 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

## CONTEXTO PARA IA (copie e cole para continuar o projeto)

> Use este bloco para explicar o projeto para qualquer IA ou desenvolvedor:

```
Projeto: HTML/CSS/JS
Tipo: Full-Stack (React + Express)
Stack: React + Vite, TypeScript, Tailwind CSS, Python, Node.js + Express, PostgreSQL, Drizzle ORM
Arquivos: 116 | Linhas: ~14.021
Rotas API: 13 endpoint(s) detectado(s)
Variaveis de ambiente necessarias: DATABASE_URL, SESSION_SECRET, PORT, AI_INTEGRATIONS_OPENAI_API_KEY, AI_INTEGRATIONS_OPENAI_BASE_URL, REPL_ID

Estrutura principal:
  SISTEMA.md
  client/index.html
  client/public/auditoria.html
  client/public/codigo-formatacao.txt
  client/public/comparador.html
  client/public/favicon.png
  client/public/manifest.json
  client/public/sw.js
  client/replit_integrations/audio/audio-playback-worklet.js
  client/replit_integrations/audio/audio-utils.ts
  client/replit_integrations/audio/index.ts
  client/replit_integrations/audio/useAudioPlayback.ts
  client/replit_integrations/audio/useVoiceRecorder.ts
  client/replit_integrations/audio/useVoiceStream.ts
  client/src/App.tsx
  client/src/components/pwa-install.tsx
  client/src/components/theme-provider.tsx
  client/src/components/theme-toggle.tsx
  client/src/components/ui/accordion.tsx
  client/src/components/ui/alert-dialog.tsx
  client/src/components/ui/alert.tsx
  client/src/components/ui/aspect-ratio.tsx
  client/src/components/ui/avatar.tsx
  client/src/components/ui/badge.tsx
  client/src/components/ui/breadcrumb.tsx
  client/src/components/ui/button.tsx
  client/src/components/ui/calendar.tsx
  client/src/components/ui/card.tsx
  client/src/components/ui/carousel.tsx
  client/src/components/ui/chart.tsx
  client/src/components/ui/checkbox.tsx
  client/src/components/ui/collapsible.tsx
  client/src/components/ui/command.tsx
  client/src/components/ui/context-menu.tsx
  client/src/components/ui/dialog.tsx
  client/src/components/ui/drawer.tsx
  client/src/components/ui/dropdown-menu.tsx
  client/src/components/ui/form.tsx
  client/src/components/ui/hover-card.tsx
  client/src/components/ui/input-otp.tsx
  client/src/components/ui/input.tsx
  client/src/components/ui/label.tsx
  client/src/components/ui/menubar.tsx
  client/src/components/ui/navigation-menu.tsx
  client/src/components/ui/pagination.tsx
  client/src/components/ui/popover.tsx
  client/src/components/ui/progress.tsx
  client/src/components/ui/radio-group.tsx
  client/src/components/ui/resizable.tsx
  client/src/components/ui/scroll-area.tsx
  client/src/components/ui/select.tsx
  client/src/components/ui/separator.tsx
  client/src/components/ui/sheet.tsx
  client/src/components/ui/sidebar.tsx
  client/src/components/ui/skeleton.tsx
  client/src/components/ui/slider.tsx
  client/src/components/ui/switch.tsx
  client/src/components/ui/table.tsx
  client/src/components/ui/tabs.tsx
  client/src/components/ui/textarea.tsx
  client/src/components/ui/toast.tsx
  client/src/components/ui/toaster.tsx
  client/src/components/ui/toggle-group.tsx
  client/src/components/ui/toggle.tsx
  client/src/components/ui/tooltip.tsx
  client/src/hooks/use-mobile.tsx
  client/src/hooks/use-toast.ts
  client/src/index.css
  client/src/lib/queryClient.ts
  client/src/lib/utils.ts
  client/src/main.tsx
  client/src/pages/auditoria-financeira.tsx
  client/src/pages/comparador-juridico.tsx
  client/src/pages/consulta-corporativo.tsx
  client/src/pages/consulta-pdpj.tsx
  client/src/pages/consulta-processual.tsx
  client/src/pages/login.tsx
  client/src/pages/not-found.tsx
  client/src/pages/painel-processos.tsx
  client/src/pages/playground.tsx
  client/src/pages/token-generator.tsx
  components.json
  dist/public/auditoria.html
  dist/public/comparador.html
  dist/public/favicon.png
  dist/public/index.html
  dist/public/manifest.json
  dist/public/sw.js
  drizzle.config.ts
  fix_buttons.txt
  main.py
  package.json
  postcss.config.js
  public/auditoria.html
  replit.md
  script/build.ts
  server/index.ts
  server/replit_integrations/audio/client.ts
  server/replit_integrations/audio/index.ts
  server/replit_integrations/audio/routes.ts
  server/replit_integrations/batch/index.ts
  server/replit_integrations/batch/utils.ts
  server/replit_integrations/chat/index.ts
  server/replit_integrations/chat/routes.ts
  server/replit_integrations/chat/storage.ts
  server/replit_integrations/image/client.ts
  server/replit_integrations/image/index.ts
  server/replit_integrations/image/routes.ts
  server/static.ts
  server/storage.ts
  server/vite.ts
  shared/models/chat.ts
  shared/schema.ts
  tailwind.config.ts
  tsconfig.json
  vite.config.ts
```

---

*Plano gerado pelo SK Code Editor — 02/05/2026, 13:16:56*