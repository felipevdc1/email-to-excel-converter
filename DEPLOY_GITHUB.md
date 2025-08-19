# 🚀 Deploy no GitHub - email-to-excel-converter

## Passo 1: Criar repositório no GitHub

1. Acesse [github.com/new](https://github.com/new)
2. Nome do repositório: `email-to-excel-converter`
3. Descrição: "Conversor de emails EML para Excel - 100% no navegador"
4. Deixe como público
5. NÃO inicialize com README (já temos)
6. Clique em "Create repository"

## Passo 2: Conectar e fazer push

Copie e cole estes comandos no terminal (na pasta WEB-DEPLOY):

```bash
# Adicionar o remote (substitua SEU_USUARIO pelo seu usuário do GitHub)
git remote add origin https://github.com/SEU_USUARIO/email-to-excel-converter.git

# Fazer push
git branch -M main
git push -u origin main
```

## Passo 3: Ativar GitHub Pages

1. No repositório, vá em **Settings** (⚙️)
2. Role até **Pages** no menu lateral
3. Em **Source**, selecione:
   - Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
4. Clique em **Save**
5. Aguarde 2-3 minutos

## 📎 URLs finais:

- **Repositório:** `https://github.com/SEU_USUARIO/email-to-excel-converter`
- **Site ao vivo:** `https://SEU_USUARIO.github.io/email-to-excel-converter`

## 🎯 Deploy em outras plataformas usando o GitHub:

### Vercel
1. Acesse [vercel.com/import](https://vercel.com/import)
2. Import Git Repository
3. Selecione `email-to-excel-converter`
4. Deploy!

### Netlify
1. Acesse [app.netlify.com](https://app.netlify.com)
2. "Import from Git"
3. Conecte GitHub
4. Selecione `email-to-excel-converter`
5. Deploy!

## 🔄 Atualizações futuras:

Para atualizar o site após mudanças:

```bash
git add .
git commit -m "Descrição da mudança"
git push
```

O site será atualizado automaticamente em 2-3 minutos!

---

**Projeto:** email-to-excel-converter
**Tecnologia:** HTML + JavaScript (client-side)
**Custo:** R$ 0,00 (gratuito)