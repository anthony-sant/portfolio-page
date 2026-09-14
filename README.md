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

https://portfolio-page-psi-brown.vercel.app

