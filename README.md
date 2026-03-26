# 🌽 Império do Cuscuz

Site de cardápio digital para o **Império do Cuscuz** — Tradição Nordestina, Ilhéus/BA.

## 🚀 Como publicar no GitHub Pages

### 1. Criar o repositório
1. Acesse [github.com](https://github.com) e faça login
2. Clique em **"New repository"** (botão verde)
3. Dê um nome ao repositório, ex: `imperio-cuscuz`
4. Deixe como **Public**
5. **Não** marque nenhuma opção extra (sem README, sem .gitignore)
6. Clique em **"Create repository"**

### 2. Enviar os arquivos

#### Opção A — Pelo site do GitHub (mais fácil)
1. Na página do repositório recém-criado, clique em **"uploading an existing file"**
2. Arraste **todos os arquivos e pastas** deste projeto para a área de upload
3. Clique em **"Commit changes"**

#### Opção B — Via Git (terminal)
```bash
git init
git add .
git commit -m "primeiro commit"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/imperio-cuscuz.git
git push -u origin main
```

### 3. Ativar o GitHub Pages
1. No repositório, vá em **Settings** → **Pages** (menu lateral)
2. Em **"Branch"**, selecione `main` e pasta `/ (root)`
3. Clique em **Save**
4. Aguarde ~1 minuto e acesse: `https://SEU-USUARIO.github.io/imperio-cuscuz`

---

## 📁 Estrutura do projeto

```
imperio-cuscuz/
├── index.html                  ← página principal
├── css/
│   └── styles.css
├── js/
│   └── app.js
└── imagens/
    ├── logo/                   ← coloque o logo aqui
    ├── hero/                   ← coloque a imagem do banner aqui
    └── produtos/               ← fotos dos produtos
```

## 🖼️ Personalização

- **Logo**: substitua o arquivo em `imagens/logo/` e atualize o `index.html`
- **Banner hero**: adicione uma imagem em `imagens/hero/`
- **Fotos dos produtos**: substitua as imagens em `imagens/produtos/`
- **WhatsApp**: o número já está configurado no código (`app.js`)

---

Feito com ❤️ para o Império do Cuscuz.
