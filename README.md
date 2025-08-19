# 📧 Conversor de Emails para Excel

Aplicação web para converter arquivos .eml (emails) de um arquivo ZIP para planilha Excel (.csv).

## 🌐 Demo Online

Você pode usar a aplicação diretamente em: [Em breve]

## ✨ Características

- 🔒 **100% Privado** - Processamento local no navegador
- 🚀 **Rápido** - Não precisa enviar arquivos para servidor
- 📊 **Completo** - Extrai todas as informações dos emails
- 💻 **Multiplataforma** - Funciona em qualquer navegador moderno
- 🎯 **Simples** - Interface intuitiva com drag & drop
- 📱 **Responsivo** - Funciona em desktop e mobile

## 🎯 Como Usar

1. Abra o arquivo `index.html` no navegador (ou acesse a versão online)
2. Arraste um arquivo ZIP contendo emails .eml
3. Aguarde o processamento
4. Baixe o arquivo CSV gerado
5. Abra no Excel ou Google Sheets

## 📋 Informações Extraídas

- Remetente e destinatários
- Assunto
- Data e hora
- Corpo do email (até 5000 caracteres)
- Quantidade de anexos
- Nomes dos anexos
- IDs de referência

## 🚀 Deploy Rápido

### Vercel (1 clique)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

### Netlify (Drag & Drop)
1. Acesse [app.netlify.com](https://app.netlify.com)
2. Arraste esta pasta para o navegador

### GitHub Pages
1. Faça fork deste repositório
2. Ative GitHub Pages nas configurações
3. Acesse `https://seu-usuario.github.io/nome-repo`

## 🛠️ Desenvolvimento Local

```bash
# Opção 1: Usando npx
npx serve .

# Opção 2: Usando Python
python3 -m http.server 8000

# Opção 3: Usando Node.js
npm install -g http-server
http-server
```

## 📦 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- [JSZip](https://stuk.github.io/jszip/) - Para extrair arquivos ZIP

## 🔒 Privacidade

- Nenhum dado é enviado para servidores
- Todo processamento acontece no seu navegador
- Arquivos são processados localmente
- Não armazenamos nenhuma informação

## 📱 Compatibilidade

- ✅ Google Chrome 60+
- ✅ Firefox 60+
- ✅ Safari 12+
- ✅ Edge 79+
- ❌ Internet Explorer (não suportado)

## 📄 Licença

MIT - Uso livre para qualquer propósito

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se livre para:
- Reportar bugs
- Sugerir melhorias
- Enviar pull requests

## 📞 Suporte

Em caso de dúvidas ou problemas:
- Abra uma issue no GitHub
- Verifique a documentação de deploy
- Teste com um arquivo ZIP pequeno primeiro

---

**Desenvolvido com ❤️ para facilitar a conversão de emails**