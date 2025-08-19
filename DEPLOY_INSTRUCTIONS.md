# 🚀 Instruções de Deploy - Conversor de Emails para Excel

Este aplicativo pode ser hospedado gratuitamente em várias plataformas. Escolha a que preferir:

## 📋 Pré-requisitos
- Conta GitHub (grátis em github.com)
- Arquivos desta pasta (`index.html` e configurações)

---

## 🔷 Opção 1: Vercel (Recomendado - Mais fácil)

### Método A: Deploy com 1 clique
1. Faça upload desta pasta para um repositório GitHub
2. Acesse [vercel.com](https://vercel.com)
3. Clique em "Import Project"
4. Conecte seu GitHub e selecione o repositório
5. Clique em "Deploy"
6. Pronto! Seu site estará no ar em segundos

### Método B: Via linha de comando
```bash
# Instale o Vercel CLI
npm i -g vercel

# Na pasta do projeto, execute:
vercel

# Siga as instruções na tela
```

**URL final:** `https://seu-projeto.vercel.app`

---

## 🟢 Opção 2: Netlify

### Método A: Drag & Drop (Mais simples)
1. Acesse [app.netlify.com](https://app.netlify.com)
2. Arraste a pasta `WEB-DEPLOY` para a área indicada
3. Pronto! Site publicado instantaneamente

### Método B: Via GitHub
1. Faça upload para GitHub
2. Em Netlify, clique "New site from Git"
3. Conecte o repositório
4. Deploy automático configurado

**URL final:** `https://seu-projeto.netlify.app`

---

## 🟣 Opção 3: GitHub Pages (100% Grátis)

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Vá em Settings → Pages
4. Source: Deploy from branch
5. Branch: main, folder: / (root)
6. Save

**URL final:** `https://seu-usuario.github.io/nome-repositorio`

---

## 🔵 Opção 4: Render

1. Acesse [render.com](https://render.com)
2. New → Static Site
3. Conecte seu repositório GitHub
4. Build Command: (deixe vazio)
5. Publish directory: `.`
6. Create Static Site

**URL final:** `https://seu-projeto.onrender.com`

---

## 🟠 Opção 5: Surge.sh (Mais rápido)

```bash
# Instale o Surge
npm install -g surge

# Na pasta do projeto
surge

# Escolha um domínio ou use o sugerido
```

**URL final:** `https://seu-escolha.surge.sh`

---

## 🟡 Opção 6: Firebase Hosting

```bash
# Instale Firebase CLI
npm install -g firebase-tools

# Inicialize
firebase init hosting

# Deploy
firebase deploy
```

**URL final:** `https://seu-projeto.web.app`

---

## ⚡ Deploy Rápido para Teste

### Usando npx serve (localhost)
```bash
npx serve .
# Acesse http://localhost:3000
```

### Usando Python (se tiver instalado)
```bash
python3 -m http.server 8000
# Acesse http://localhost:8000
```

---

## 🔧 Configurações Incluídas

- `vercel.json` - Configuração para Vercel
- `netlify.toml` - Configuração para Netlify
- `package.json` - Dependências e scripts

---

## 🌐 Domínio Personalizado

Todas as plataformas acima permitem usar domínio próprio gratuitamente:
1. Compre um domínio (ex: no Registro.br)
2. Configure o DNS apontando para a plataforma
3. Adicione o domínio nas configurações do projeto

---

## 📱 Funcionalidades da Aplicação

✅ Processamento 100% no navegador (privado)
✅ Suporta arquivos ZIP com múltiplos .eml
✅ Exporta para CSV (abre no Excel)
✅ Interface responsiva (funciona no celular)
✅ Não precisa backend/servidor
✅ Funciona offline após primeira carga

---

## 🆘 Suporte

Problemas comuns:
- **Arquivo muito grande**: Funciona com ZIPs até ~200MB
- **Navegador antigo**: Use Chrome, Firefox, Safari ou Edge recentes
- **Deploy falhou**: Verifique se todos os arquivos estão na pasta

---

## 📊 Estatísticas Esperadas

- Tempo de deploy: < 1 minuto
- Custo: R$ 0 (grátis)
- Uptime: 99.9%
- Limite de uso: Ilimitado
- SSL/HTTPS: Incluído gratuitamente

---

**Escolha a plataforma que preferir e tenha seu conversor online em minutos!** 🎉