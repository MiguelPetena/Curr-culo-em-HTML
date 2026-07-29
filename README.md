# Portfólio — Miguel Petená

Site estático de página única (`index.html`), sem build necessário.

## Antes de publicar

E-mail, telefone, LinkedIn e o botão "Baixar currículo (PDF)" já estão preenchidos com seus dados reais e o arquivo `curriculo-miguel-petena.pdf` (incluído nesta pasta). Se quiser adicionar GitHub, busque a seção `<ul class="contact-list">` no `index.html` e inclua um novo `<li>`.

Se atualizar o currículo no futuro, basta substituir o arquivo `curriculo-miguel-petena.pdf` por uma nova versão com o mesmo nome — o botão continuará funcionando.

## Publicar na Vercel

**Opção 1 — pelo site (mais simples):**
1. Acesse https://vercel.com/new
2. Escolha "Deploy" > arraste a pasta `portfolio` (ou faça upload do `index.html`)
3. Confirme — a Vercel detecta automaticamente como site estático

**Opção 2 — via GitHub:**
1. Suba esta pasta para um repositório no GitHub
2. Em https://vercel.com/new, importe o repositório
3. Framework Preset: "Other" (site estático) — não precisa de comandos de build
4. Deploy

**Opção 3 — via CLI:**
```bash
npm i -g vercel
cd portfolio
vercel
```
