# 🔐 VaultKey — Gerenciador de Senhas

Um gerenciador de senhas pessoal, bonito e funcional. Roda 100% no navegador — sem backend, sem servidor.

## ✨ Funcionalidades

- **Login com senha mestra** — acesse só com seu usuário + senha
- **Abas personalizadas** — crie abas como "Jogos", "Trabalho", "Redes Sociais"
- **Salvar credenciais** — nome, login/email, senha, URL e notas
- **Copiar com 1 clique** — copia login ou senha sem precisar ver
- **Indicador de força** — avalia a força de cada senha
- **Busca** — encontre qualquer credencial rapidamente
- **Exportar backup** — baixe um JSON com seus dados
- **100% offline** — dados ficam no localStorage do seu navegador

---

## 🚀 Como hospedar no Vercel (gratuito)

### Opção 1: Deploy via GitHub (recomendado)

1. Crie uma conta gratuita em [vercel.com](https://vercel.com)
2. Crie um repositório no GitHub e suba os arquivos:
   ```
   index.html
   vercel.json
   ```
3. No Vercel: **Add New Project** → importe o repositório do GitHub
4. Clique em **Deploy** — pronto! Você receberá uma URL do tipo `https://seusite.vercel.app`

### Opção 2: Deploy via Vercel CLI

```bash
npm install -g vercel
cd pasta-do-projeto
vercel
```

### Outras opções gratuitas

| Plataforma | Como fazer |
|---|---|
| **Netlify** | Arraste a pasta para [app.netlify.com/drop](https://app.netlify.com/drop) |
| **GitHub Pages** | Suba para um repo público e ative Pages nas configurações |
| **Cloudflare Pages** | Conecte o GitHub no [pages.cloudflare.com](https://pages.cloudflare.com) |

---

## ⚠️ Importante sobre segurança

- As senhas ficam no **localStorage** do seu navegador
- **Não compartilhe o link** com outras pessoas (elas não verão seus dados, mas você perde privacidade)
- Use o botão **Exportar** regularmente para fazer backup
- Para mais segurança, use em modo privado ou em um navegador dedicado

---

## 📁 Estrutura

```
/
├── index.html     # App completo (HTML + CSS + JS)
└── vercel.json    # Configuração do Vercel
```
