# Portfolio Page

Este repositório contém duas áreas independentes:

- `portfolio-web/`: frontend Vue 3 + Vite canônico e publicado.
- `demo/`: backend Java reservado para integração futura. Ele não faz parte do
  frontend nem deve ser executado para desenvolver ou publicar o portfólio.

## Frontend

Todos os comandos do frontend devem ser executados em `portfolio-web/`:

```bash
cd portfolio-web
npm ci
npm run dev
```

Para gerar a versão de produção:

```bash
cd portfolio-web
npm run build
```

O build é criado em `portfolio-web/dist/`.

## Deploy na Vercel

Importe este repositório e configure **Root Directory** como `portfolio-web`.
A Vercel então usará `portfolio-web/package.json` e o rewrite de SPA definido
em `portfolio-web/vercel.json`. Não use a raiz do repositório como diretório de
build, pois ela não contém uma aplicação Vue.

## Contatos

Os dados de contato ficam em `portfolio-web/src/data/contact-content.js`. O
link do GitHub aponta para o repositório configurado. Atualize os campos de
e-mail e LinkedIn, que permanecem como placeholders, antes de publicar dados
de contato pessoais.