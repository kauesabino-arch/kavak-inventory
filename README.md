# 📦 Kavak Inventory — PWA

App de inventário como Progressive Web App. Funciona em qualquer celular via navegador.

---

## 🚀 Como hospedar no GitHub Pages (5 minutos)

### Passo 1 — Crie um repositório no GitHub
1. Acesse **github.com** e faça login
2. Clique em **"New repository"**
3. Nome: `kavak-inventory`
4. Deixe **público**
5. Clique em **"Create repository"**

### Passo 2 — Suba os arquivos
Na página do repositório criado, clique em **"uploading an existing file"** e arraste todos os arquivos:
- `index.html`
- `manifest.json`
- `icon-192.png`
- `icon-512.png`

Clique em **"Commit changes"**.

### Passo 3 — Ative o GitHub Pages
1. Vá em **Settings** do repositório
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione **Deploy from a branch**
4. Branch: **main**, pasta: **/ (root)**
5. Clique em **Save**

Aguarde ~1 minuto. O link do app vai aparecer no topo da página:
```
https://SEU-USUARIO.github.io/kavak-inventory
```

### Passo 4 — Configure o Google Sheets
No arquivo `index.html`, na linha:
```javascript
const GAS_URL = 'YOUR_GOOGLE_APPS_SCRIPT_URL_HERE';
```
Substitua pela URL do seu Google Apps Script.

---

## 📱 Como instalar no celular Android

1. Manda o link por WhatsApp para os colaboradores
2. Eles abrem o link no **Chrome**
3. Chrome vai mostrar um banner "Adicionar à tela inicial" — toca em **Adicionar**
4. O app aparece na tela inicial como ícone normal!

---

## 👤 Acesso padrão

| Usuário | Senha    | Função |
|---------|----------|--------|
| admin   | admin123 | Admin  |

---

## ✅ Funcionalidades

- Login com usuário e senha
- Leitura de QR Code pela câmera
- Entrada manual como fallback
- Histórico de registros
- Sincronização com Google Sheets
- Modo offline (dados salvos no dispositivo)
- 3 níveis de acesso: Colaborador, Supervisor, Admin
- Painel admin para gerenciar usuários
