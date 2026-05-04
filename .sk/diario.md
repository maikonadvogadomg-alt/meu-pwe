# Diário de Progresso

## 04/05/2026
### ✅ Concluído
- Criado `.sk/indice.md` com mapa geral do projeto.
- Criado `.sk/perfil-jasmim.md` com preferências de trabalho e contexto do Saulo.
- Criado `.sk/diario.md` para registrar o histórico técnico da recuperação.
- Criado `_jasmim/RESUMO.md` com resumo da sessão.
- Criado `_jasmim/PROXIMOS_PASSOS.md` com fluxo sem terminal.
- Criado `_jasmim/DIAGNOSTICO_INICIAL.md` com avaliação inicial do PWA principal.
- Definido que este PWA é a oficina principal a ser preservada.

### 🔄 Alterado
- Organização documental do projeto para permitir retomada rápida.
- Definido que o fluxo principal de trabalho será sem terminal local, usando GitHub → StackBlitz/VS Code Web quando precisar executar algo.
- Definido critério de auditoria por status: salvar, desacoplar ou substituir.

### ⏳ Pendente
- Auditoria estrutural de:
  - `server/index.ts`
  - `server/storage.ts`
  - `shared/schema.ts`
  - `client/src/App.tsx`
  - `client/src/pages/login.tsx`
  - `server/replit_integrations/*`
  - `client/replit_integrations/audio/*`
- Confirmar como o login depende de configuração.
- Confirmar como o banco Neon está ligado ao projeto.
- Confirmar o que ainda está preso à Replit.
- Revisar o fluxo PWA → APK.
- Verificar se o service worker está segurando versões antigas.

### 🐛 Bugs / Riscos conhecidos
- Terminal local não funciona neste ambiente.
- Projeto possui integrações específicas da Replit.
- Há risco de partes críticas estarem funcionando só parcialmente.
- Algumas funções automáticas do PWA sumiram ou estão inconsistentes segundo o relato do Saulo.
- Pode haver comportamento de login condicionado a variáveis/configuração.

### 📌 Próximos passos
1. Auditar o núcleo do backend.
2. Auditar autenticação/login.
3. Auditar dependências Replit.
4. Auditar PWA/cache/publicação.
5. Documentar o diagnóstico em `_jasmim/`.