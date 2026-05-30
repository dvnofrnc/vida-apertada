# Vida Apertada · PWA

Gestão financeira mensal pessoal.

## Como publicar no GitHub Pages (para gerar APK)

### Passo 1 — Criar repositório no GitHub
1. Acesse https://github.com e faça login (ou crie conta gratuita)
2. Clique em **"New repository"** (botão verde)
3. Nome: `vida-apertada`
4. Deixe como **Public**
5. Clique em **"Create repository"**

### Passo 2 — Fazer upload dos arquivos
1. Na página do repositório, clique em **"uploading an existing file"**
2. Arraste **todos** os arquivos desta pasta (index.html, manifest.json, sw.js, .nojekyll e a pasta icons/)
3. Clique em **"Commit changes"**

### Passo 3 — Ativar GitHub Pages
1. Vá em **Settings** (na barra do repositório)
2. Menu lateral → **Pages**
3. Em "Branch", selecione **main** → **/root**
4. Clique em **Save**
5. Aguarde ~2 minutos. A URL do site aparecerá: `https://SEU_USUARIO.github.io/vida-apertada`

### Passo 4 — Gerar o APK
1. Acesse https://www.pwabuilder.com
2. Cole sua URL do GitHub Pages
3. Clique em **"Start"**
4. Vá em **Android** → **"Generate Package"**
5. Baixe o APK e instale no celular

> No Android, antes de instalar: Configurações → Segurança → ativar "Fontes desconhecidas"
