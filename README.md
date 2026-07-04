# Obscury Fraternity — Vercel Ready

Projeto estático pronto para subir no Vercel.

## Como publicar

### Opção 1 — Upload direto no Vercel
1. Extraia o arquivo `.zip`.
2. Envie a pasta `obscury-vercel` para um repositório no GitHub.
3. No Vercel, clique em **Add New Project** e importe o repositório.
4. Framework: **Other** / **Static**.
5. Build Command: deixe vazio ou use `npm run build`.
6. Output Directory: deixe vazio se não usar build, ou use `dist` se usar `npm run build`.

### Opção 2 — Vercel CLI
```bash
npm i -g vercel
cd obscury-vercel
vercel
```

O site principal está em `index.html`.
