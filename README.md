# 🎉 Site de Aniversário da Ana

Um site interativo de aniversário, em página única, com fotos e música embutidas.
Tudo está dentro do `index.html` — não há dependências externas.

---

## Como colocar no ar (GitHub + Render)

### Parte 1 — Subir no GitHub

1. Crie uma conta em https://github.com (se ainda não tiver).
2. Clique em **New repository** (botão verde).
3. Dê um nome, por exemplo: `aniversario-ana`.
4. Deixe como **Public**, NÃO marque "Add a README" (já temos um).
5. Clique em **Create repository**.
6. Na página seguinte, clique em **uploading an existing file**.
7. Arraste TODOS os arquivos desta pasta para lá:
   - `index.html`
   - `render.yaml`
   - `README.md`
8. Clique em **Commit changes**.

### Parte 2 — Dar deploy no Render

1. Crie uma conta em https://render.com (pode entrar com o GitHub).
2. No painel, clique em **New +** → **Static Site**.
3. Conecte sua conta do GitHub e selecione o repositório `aniversario-ana`.
4. O Render vai detectar o `render.yaml` automaticamente. Confirme as configurações:
   - **Build Command:** (deixe vazio)
   - **Publish Directory:** `.`
5. Clique em **Create Static Site**.
6. Aguarde alguns segundos. O Render vai te dar um link tipo:
   `https://aniversario-ana.onrender.com`
7. Pronto! É esse link que você manda para a Ana. 💖

---

## Observação sobre a música 🎵

Navegadores de celular bloqueiam áudio que toca sozinho sem nenhum toque do
usuário. Como a Ana vai clicar nos botões ao longo do site, na maioria das vezes
a música toca sozinha na última página. Se for bloqueada, existe um botão
**"🎵 Tocar música"** de reserva — basta um toque para a música começar e
ficar em loop.
