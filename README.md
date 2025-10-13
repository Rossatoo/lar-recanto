# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
.
├─ public/                          # arquivos estáticos (imagens, favicon, og.jpg, etc.)
│  ├─ hero-senior.jpg
│  ├─ logo.jpg
│  └─ favicon.svg
├─ src/
│  ├─ assets/                       
│  ├─ components/                   # componentes de UI (seções da landing)
│  │  ├─ Contato.astro
│  │  ├─ Depoimentos.astro
│  │  ├─ Features.astro
│  │  ├─ Footer.astro
│  │  ├─ Hero.astro
│  │  ├─ Navbar.astro
│  │  ├─ Servicos.astro
│  ├─ layouts/                      # layouts compartilhados
│  │  ├─ Base.astro                 # layout principal (head, fontes, <slot/>)
│  │  └─ Layout.astro               # (se precisar de outro layout)
│  ├─ pages/                        # rotas do site (cada arquivo vira uma página)
│  │  └─ index.astro                # página inicial
│  └─ styles/
│     └─ global.css                 # Tailwind v4 + utilitárias do tema
├─ .gitignore
├─ astro.config.mjs                 # config do Astro (+ plugin @tailwindcss/vite)
├─ package.json                     # scripts e dependências
├─ package-lock.json
├─ README.md
└─ tsconfig.json

```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
