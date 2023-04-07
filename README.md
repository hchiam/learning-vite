# Learning Vite [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://github.com/hchiam/learning-template/blob/main/LICENSE)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Quick tip/reminder: already installed `vite`? If you have an `index.html` file in the current directory, just run this:

```bash
vite
```

Speed up server start and development by leveraging modern ES modules in the browser for faster development time. Vite transforms and serves source code only on demand. You still will want to bundle for production or final testing, but not during development where files are constantly being updated. Vite can translate `import { someMethod } from 'my-dep'` for the browser, so you don't have to think about it. Out of the box, you can directly import `.ts` files (and [other file types too](https://vitejs.dev/guide/features.html#json)), and `@import` CSS files or `import classes from './example.module.css'`. Vite comes with things like code-splitting and load optimizations on by default.

https://vitejs.dev

https://vitejs.dev/guide

https://github.com/vitejs/vite

## Note to self - if js file doesn't seem to get added to /dist

```html
<script src="index.js"></script>
```

needs to be

```html
<script type="module" src="index.js"></script>
```

## Online

https://vite.new/

https://vite.new/react-ts

`https://vite.new/{template}` <-- see [template link list](https://vitejs.dev/guide/#trying-vite-online)

## From scratch

Using [`yarn`](https://github.com/hchiam/learning-yarn):

```bash
yarn create vite
# and follow prompts
```

Or with `npm`:

```bash
npm init vite@latest
# and follow prompts
```

Then `cd` into the project folder and run `yarn; yarn dev`

```json
{
  "scripts": {
    "dev": "vite", // start dev server, aliases: `vite dev`, `vite serve`
    "build": "vite build", // build for production
    "preview": "vite preview" // locally preview production build
  }
}
```

## Starting with a minimal repo example

https://github.com/hchiam/vite-project-example-minimal

## Starting by testing out this repo

Using [`yarn`](https://github.com/hchiam/learning-yarn): (triple-click to select all)

```bash
git clone https://github.com/hchiam/learning-vite.git && cd learning-vite/vite-project-example && yarn && yarn dev;
```

Or with `npm`: (triple-click to select all)

```bash
git clone https://github.com/hchiam/learning-vite.git && cd learning-vite/vite-project-example && npm install && npm run dev;
```

Then open http://localhost:3000

## Commands, explained

```json
{
  "scripts": {
    "dev": "vite", // start dev server, aliases: `vite dev`, `vite serve`
    "build": "vite build", // build for production
    "preview": "vite preview" // locally preview production build
  }
}
```
