# Consagração a Nossa Senhora — site

Site estático com a página inicial, os 8 encontros (apresentações) e os materiais em PDF.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `consagracao`).
2. Envie **todos** os arquivos desta pasta para a raiz do repositório (mantendo a pasta `assets/`).
3. No repositório: **Settings → Pages**.
4. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
5. Em **Branch**, selecione `main` e a pasta `/ (root)`. Salve.
6. Aguarde 1–2 minutos. O site ficará em `https://SEU-USUARIO.github.io/consagracao/`.

A página que abre é `index.html` (a mesma da tela inicial).

## Arquivos

- `index.html` — página inicial (idêntica a `Inicio.dc.html`).
- `Encontro-1` … `Encontro-8` `.dc.html` — as apresentações.
- `Inicio.dc.html` — cópia de trabalho da página inicial.
- `deck-stage.js`, `support.js` — runtime das páginas (necessários).
- `assets/` — imagens (Nossa Senhora, emblema).
- `.nojekyll` — impede o GitHub Pages de ignorar arquivos.

## PDFs (colocar na raiz, com estes nomes exatos)

Os cards de materiais da página inicial apontam para:

- `33-Dias-de-Exercicios-Espirituais-e-Oracoes.pdf`
- `Tratado-da-Verdadeira-Devocao.pdf`

Coloque os dois PDFs na raiz do repositório com **exatamente** esses nomes (sem acento, sem espaços) e os links funcionarão.

## Navegar

Setas do teclado avançam os slides de cada encontro. A trilha de miniaturas permite pular e reordenar.
