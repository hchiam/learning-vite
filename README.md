# Learning Vite [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://github.com/hchiam/learning-template/blob/main/LICENSE)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Speed up server start and development by leveraging modern ES modules in the browser for faster development time. Vite transforms and serves source code only on demand. You still will want to bundle for production or final testing, but not during development where files are constantly being updated.

https://vitejs.dev

https://vitejs.dev/guide

https://github.com/vitejs/vite

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

## Starting by testing out this repo <!-- Replace "template"s and "# and then ..."s in this section -->

Using [`yarn`](https://github.com/hchiam/learning-yarn): (triple-click to select all)

```bash
git clone https://github.com/hchiam/learning-vite.git && cd learning-vite/vite-project-example && yarn; # and then ...
```

Or with `npm`: (triple-click to select all)

```bash
git clone https://github.com/hchiam/learning-vite.git && cd learning-vite/vite-project-example && npm install; # and then ...
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
