# AUDIOVERSE Website

Este é o site oficial da AUDIOVERSE, preparado em HTML/CSS/JS puro, bilingue (PT/EN) e com formulário de contacto.

---

## 📂 Estrutura
```
AUDIOVERSE_SITE_FULL_v2/
│
├── index.html        # Página principal (toggle PT/EN, serviços, contactos, formulário)
├── thanks.html       # Página de obrigado (após envio do formulário)
├── assets/           # Pasta para imagens (colocar logo.png e logo-large.png)
└── README.md         # Este guia
```

---

## 🚀 Como usar localmente
1. Extrai o `.zip` para uma pasta no teu computador.
2. Coloca os ficheiros do logo dentro da pasta `assets/`:
   - `logo.png` (versão pequena para o topo/navbar)
   - `logo-large.png` (versão maior para a secção hero)
3. Dá duplo clique em `index.html` para abrir no navegador.

---

## 🌍 Publicar o site online
### Opção 1 — [Netlify](https://www.netlify.com/)
1. Cria uma conta gratuita.
2. Carrega a pasta inteira (`AUDIOVERSE_SITE_FULL_v2`).
3. Netlify gera um link gratuito imediato (ex: `https://audioverse.netlify.app`).

### Opção 2 — [Vercel](https://vercel.com/)
1. Cria uma conta gratuita.
2. Faz drag & drop da pasta ou liga ao GitHub com o projeto.
3. O site fica online em minutos.

### Opção 3 — GitHub Pages
1. Cria um repositório no GitHub e envia os ficheiros.
2. Vai a **Settings → Pages** e ativa a publicação.
3. O site ficará acessível em `https://teu-utilizador.github.io/audioverse/`.

---

## 📧 Formulário de contacto
- O formulário usa [FormSubmit](https://formsubmit.co/) — não precisa de backend.
- Já está configurado para enviar para `audioverse@gmail.com`.
- Ao submeter, o visitante é redirecionado para `thanks.html`.

### ⚠️ Recomendações:
- Para maior controlo, cria uma conta no [FormSubmit](https://formsubmit.co/) e valida o teu email.
- Se no futuro quiseres algo mais avançado, podes integrar Google Forms, Typeform, ou backend próprio.

---

## 🔧 Personalização rápida
- Muda cores e estilos no `<style>` dentro do `index.html`.
- Edita os textos bilingues no objeto `i18n` dentro do `<script>`.

---

## 📌 Próximos passos
- [ ] Publicar no Netlify ou Vercel.
- [ ] Testar o formulário e confirmar receção no `audioverse@gmail.com`.
- [ ] Criar domínio próprio (ex: `audioverse.pt`) e apontar para o site.

---

Feito com ❤️ para AUDIOVERSE.
