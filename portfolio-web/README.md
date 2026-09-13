# Portfolio Page Frontend

Aplicação canônica do portfólio, construída com Vue 3 e Vite. Execute todos os
comandos desta documentação dentro de `portfolio-web/`.

## Requisitos

- Node.js 20.19+ (linha 20) ou 22.12+
- npm

## Instalação

```bash
npm ci
```

## Desenvolvimento

```bash
npm run dev
```

O Vite exibirá a URL local da aplicação.

## Build de produção

```bash
npm run build
```

Os arquivos estáticos são gerados em `dist/`. Para inspecioná-los localmente:

```bash
npm run preview
```

## Deploy na Vercel

Ao importar o repositório, defina **Root Directory** como `portfolio-web`.
O `vercel.json` deste diretório redireciona solicitações para `index.html`,
preservando o funcionamento das rotas do Vue Router em acessos diretos e
atualizações de página.

## Rotas SPA

| Rota | Página |
| --- | --- |
| `/` | Início |
| `/sobre` | Sobre |
| `/projetos` | Projetos |
| `/experiencias` | Experiências |
| `/contato` | Contato |

## Configuração de contatos

Edite `src/data/contact-content.js` para configurar os contatos exibidos no
site. Os valores de e-mail, LinkedIn e GitHub são placeholders e devem ser
substituídos por informações reais antes do deploy.
