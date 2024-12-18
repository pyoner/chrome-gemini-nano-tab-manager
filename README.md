# Svelte Typescript Chrome Extension Boilerplate

Boilerplate for Chrome Extension Svelte Typescript project.

## Features

-   [Svelte](https://svelte.dev/)
-   [TypeScript](https://www.typescriptlang.org/)
-   [Vite](https://vitejs.dev/)
-   [CRXJS Vite Plugin](https://github.com/crxjs/chrome-extension-tools/blob/main/packages/vite-plugin/README.md)
-   [Chrome Extensions Manifest V3](https://developer.chrome.com/docs/extensions/mv3/intro/)

## Demo

![Demo](/demo.gif)

## Examples of integrations

-   [Tailwind CSS](https://tailwindcss.com/) – is in the [tailwindcss](https://github.com/NekitCorp/chrome-extension-svelte-typescript-boilerplate/tree/tailwindcss) branch

## Development

```bash
# install dependencies
npm i

# build files to `/dist` directory
# HMR for extension pages and content scripts
npm run dev
```

### Load unpacked extensions

[Getting Started Tutorial](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked)

1. Open the Extension Management page by navigating to `chrome://extensions`.
2. Enable Developer Mode by clicking the toggle switch next to `Developer mode`.
3. Click the `LOAD UNPACKED` button and select the `/dist` directory.

## Build

```bash
# build files to `/dist` directory
$ npm run build
```
