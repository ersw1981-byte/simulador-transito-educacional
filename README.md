# 🚗 Simulador de Movimento e Trânsito - PWA

## 📱 Progressive Web App Instalável

Este é o **Simulador de Movimento e Trânsito** desenvolvido por **Eduardo Roberto da Silva Wanderley** (UFPB/PROFMAT) em formato PWA (Progressive Web App) - pode ser instalado como um aplicativo nativo!

---

## 🚀 Como Usar

### Opção 1: Uso Online (Navegador)

1. Hospede os arquivos em qualquer servidor web
2. Acesse pelo navegador (Chrome, Edge, Firefox, Safari)
3. Use normalmente!

### Opção 2: Instalar como App

#### 📱 No Celular (Android/iOS):

1. Abra o site no **Chrome** (Android) ou **Safari** (iOS)
2. Um botão **"📲 Instalar App"** aparecerá no canto inferior direito
3. Clique no botão OU:
   - **Android (Chrome)**: Menu (⋮) → "Instalar app" ou "Adicionar à tela inicial"
   - **iOS (Safari)**: Botão compartilhar → "Adicionar à Tela de Início"
4. Pronto! O app aparecerá como ícone na tela inicial

#### 💻 No Computador (Desktop):

1. Abra no **Chrome**, **Edge** ou **Brave**
2. Clique no botão **"📲 Instalar App"** OU
3. Clique no ícone de instalação (➕) na barra de endereço
4. Confirme a instalação
5. O app abrirá em janela própria, como app nativo!

---

## 🌐 Como Hospedar (Opções Gratuitas)

### 1️⃣ GitHub Pages (Recomendado)

```bash
# 1. Crie um repositório no GitHub
# 2. Faça upload de todos os arquivos da pasta pwa-simulador
# 3. Vá em Settings → Pages
# 4. Selecione branch "main" e pasta "root"
# 5. Salve e aguarde alguns minutos
# 6. Seu app estará em: https://seu-usuario.github.io/nome-do-repo
```

**Vantagens:**
- ✅ Totalmente gratuito
- ✅ HTTPS automático (obrigatório para PWA)
- ✅ Fácil de atualizar

### 2️⃣ Vercel

```bash
# 1. Instale Vercel CLI: npm install -g vercel
# 2. Entre na pasta: cd pwa-simulador
# 3. Execute: vercel
# 4. Siga as instruções
# 5. Pronto! URL automática gerada
```

**Vantagens:**
- ✅ Deploy automático
- ✅ HTTPS automático
- ✅ Muito rápido

### 3️⃣ Netlify

```bash
# 1. Crie conta em netlify.com
# 2. Arraste a pasta pwa-simulador para o site
# 3. Pronto! URL gerada automaticamente
```

### 4️⃣ Firebase Hosting

```bash
# 1. Instale: npm install -g firebase-tools
# 2. Execute: firebase init hosting
# 3. Deploy: firebase deploy
```

---

## 📂 Estrutura de Arquivos

```
pwa-simulador/
├── index.html          # Página principal
├── app.jsx            # Componente React (com logos incorporadas)
├── manifest.json      # Configuração da PWA
├── sw.js             # Service Worker (funcionalidade offline)
├── icon-192.png      # Ícone 192x192
├── icon-512.png      # Ícone 512x512
└── README.md         # Este arquivo
```

---

## ✨ Funcionalidades da PWA

✅ **Instalável** - Funciona como app nativo  
✅ **Offline** - Funciona sem internet após primeira visita  
✅ **Responsivo** - Adapta a qualquer tela  
✅ **Rápido** - Cache inteligente  
✅ **Ícone na tela inicial** - Como qualquer app  
✅ **Atualizações automáticas** - Sempre a versão mais recente  

---

## 🔧 Requisitos Técnicos

- Servidor web com **HTTPS** (obrigatório para PWA)
- Navegadores modernos:
  - ✅ Chrome/Edge 67+
  - ✅ Safari 11.1+
  - ✅ Firefox 58+
  - ✅ Samsung Internet 8+

---

## 🎓 Créditos

**Desenvolvedor:** Eduardo Roberto da Silva Wanderley  
**Instituição:** UFPB (Universidade Federal da Paraíba)  
**Programa:** PROFMAT (Mestrado Profissional em Matemática)  

**Aplicativo educacional:** Funções Matemáticas + Física aplicadas à segurança no trânsito

---

## 📝 Licença

© 2025 - Todos os direitos reservados

---

## 🆘 Suporte

### Problemas Comuns:

**❓ Botão de instalação não aparece?**
- Verifique se está usando HTTPS
- Tente em outro navegador (Chrome recomendado)
- Limpe o cache e recarregue

**❓ App não funciona offline?**
- Abra pelo menos uma vez com internet
- O cache será criado automaticamente

**❓ Como atualizar o app?**
- Recarregue a página
- O Service Worker detectará atualizações automaticamente

---

## 🚀 Próximos Passos

1. Hospede em GitHub Pages/Vercel/Netlify
2. Compartilhe o link com seus alunos
3. Eles poderão instalar como app!

**Boa sorte com seu aplicativo educacional! 📚🎓**
