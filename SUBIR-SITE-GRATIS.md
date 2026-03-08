# Subir o site de graça (hospedagem + URL grátis)

**Importante:** O site **dominiogratis.com.br** é para *comprar/vender domínios*, não para hospedar sites. Para colocar este projeto no ar **sem pagar**, use uma destas opções:

---

## Opção 1: Netlify (recomendado)

1. Crie uma conta grátis em **[netlify.com](https://www.netlify.com)**.
2. **Add new site** → **Import an existing project**.
3. Conecte **GitHub** (ou GitLab/Bitbucket).  
   Se o código ainda não estiver no GitHub:
   - Na pasta do projeto:
     ```bash
     git init
     git add .
     git commit -m "Deploy"
     ```
   - Crie um repositório no GitHub e envie:
     ```bash
     git remote add origin https://github.com/SEU-USUARIO/SEU-REPO.git
     git branch -M main
     git push -u origin main
     ```
4. No Netlify, escolha o repositório e clique **Deploy site** (o `netlify.toml` já configura o build).
5. Pronto. Seu site ficará em: **`https://[nome].netlify.app`** (URL grátis).

---

## Opção 2: Vercel (ótimo para Next.js)

1. Crie uma conta grátis em **[vercel.com](https://vercel.com)**.
2. **Add New** → **Project** → conecte **GitHub** (ou faça upload da pasta).
3. Selecione o repositório do projeto e clique **Deploy**.
4. Pronto. Seu site ficará em: **`https://[nome].vercel.app`** (URL grátis).

---

## Resumo

| Onde subir | URL grátis que você ganha |
|------------|----------------------------|
| **Netlify** | `https://seu-projeto.netlify.app` |
| **Vercel**  | `https://seu-projeto.vercel.app` |

Depois, se quiser um **domínio próprio** (ex: `seusite.com.br`), você pode comprar em um registrador (Registro.br, GoDaddy, etc.) e **apontar** esse domínio para o Netlify ou Vercel (eles explicam isso no painel).

Mais detalhes: veja **DEPLOY.md** neste projeto.
