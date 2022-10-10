# My First [Astro](https://astro.build) Project

## 🖥️ Preview screen

[![Live Demo](https://github.com/dwilson-coder/astro-crash-course/blob/main/src/images/screen.png)](https://github.com/dwilson-coder/astro-crash-course/blob/main/src/images/screen.png)

[![Live Demo](https://github.com/dwilson-coder/astro-crash-course/blob/main/src/images/demo.png)](https://first-astro-project.netlify.app/)

## 📂 Folder Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 👨‍💻 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                             |
| :--------------------- | :------------------------------------------------- |
| `npm install`          | Installs dependencies                              |
| `npm run dev`          | Starts local dev server at `localhost:3000`        |
| `npm run build`        | Build your production site to `./dist/`            |
| `npm run preview`      | Preview your build locally, before deploying       |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro preview` |
| `npm run astro --help` | Get help using the Astro CLI                       |

## 📄 Documentatpion

Astro's [documentation](https://docs.astro.build).
