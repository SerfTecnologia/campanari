# Valdir Campanari — Churrasco & Eventos 🔥

Site institucional para serviços de churrasco e eventos.

---

## 📁 Estrutura de arquivos

```
/
├── index.html          ← Arquivo principal do site (único arquivo necessário)
├── fotos/              ← Pasta para suas fotos (crie esta pasta)
│   ├── hero.jpg        ← Fundo da hero (1920x1080px)
│   ├── orcamento-bg.jpg← Fundo da seção orçamento (1920x1080px)
│   ├── diferencial.jpg ← Seção "Nossos Diferenciais" (800x600px)
│   ├── cardapio.jpg    ← Seção "Cardápio & Suporte" (800x600px)
│   ├── galeria-1.jpg   ← Foto galeria 1 (800x600px)
│   ├── galeria-2.jpg   ← Foto galeria 2 (800x600px)
│   ├── galeria-3.jpg   ← Foto galeria 3 (800x600px)
│   ├── galeria-4.jpg   ← Foto galeria 4 (800x600px)
│   ├── galeria-5.jpg   ← Foto galeria 5 (800x600px)
│   └── galeria-6.jpg   ← Foto galeria 6 (800x600px)
└── README.md
```

---

## ✏️ O que personalizar no index.html

### 📱 WhatsApp
Busque no arquivo por `wa.me/5514996002338` e troque pelo seu número:
```
wa.me/55 + DDD + NÚMERO
Exemplo: wa.me/5511999887766
```
A mensagem pré-preenchida está após `?text=` — edite conforme quiser.

### 📘 Facebook
Busque por `facebook.com/valdir.campanari` e troque pela URL da sua página.

### 🖼️ Imagens
Todas as imagens têm comentários `📸 INSIRA SUA FOTO AQUI` no HTML.
Basta substituir o `src` pelo caminho da sua foto na pasta `fotos/`.

**Tamanhos recomendados:**
| Local | Tamanho | Proporção |
|-------|---------|-----------|
| Hero (topo) | 1920 × 1080 px | 16:9 |
| Fundo Orçamento | 1920 × 1080 px | 16:9 |
| Diferenciais | 800 × 600 px | 4:3 |
| Cardápio | 800 × 600 px | 4:3 |
| Galeria | 800 × 600 px | 4:3 |

### 📝 Textos
Todos os textos estão diretamente no HTML. Busque e substitua conforme necessário.

---

## 🚀 Como subir no GitHub Pages (hospedagem gratuita)

### Passo 1 — Criar conta e repositório
1. Acesse [github.com](https://github.com) e crie uma conta (gratuito)
2. Clique em **"New repository"**
3. Nome do repositório: `campanari` (ou qualquer nome)
4. Marque como **Public**
5. Clique em **"Create repository"**

### Passo 2 — Enviar os arquivos
**Opção A — Pelo navegador (mais fácil):**
1. Na página do repositório, clique em **"uploading an existing file"**
2. Arraste o `index.html` e a pasta `fotos/` para a área
3. Clique em **"Commit changes"**

**Opção B — Via Git (terminal):**
```bash
git init
git add .
git commit -m "primeiro commit"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/campanari.git
git push -u origin main
```

### Passo 3 — Ativar GitHub Pages
1. No repositório, vá em **Settings** → **Pages**
2. Em "Source", selecione **"Deploy from a branch"**
3. Branch: **main** / Folder: **/ (root)**
4. Clique em **Save**
5. Aguarde ~2 minutos e acesse: `https://SEU_USUARIO.github.io/campanari`

---

## 🌐 Domínio personalizado (opcional)
Se quiser usar um domínio próprio (ex: `valdircampanari.com.br`):
1. Compre o domínio em Registro.br, HostGator, GoDaddy etc.
2. No GitHub Pages (Settings → Pages), insira seu domínio em **"Custom domain"**
3. No painel do seu provedor de domínio, crie registros DNS:
   - Tipo A apontando para os IPs do GitHub Pages:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
4. Aguarde até 48h para propagar

---

## ⚡ Dicas de performance
- Salve as fotos no formato **WebP** para carregamento mais rápido
- Comprima as imagens em [squoosh.app](https://squoosh.app) antes de enviar
- O site já usa `loading="lazy"` nas imagens da galeria

---

## 📞 Suporte
Desenvolvido por [Serf Tecnologia](https://www.serftecnologia.com.br)
