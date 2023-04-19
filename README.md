# Vue 3 + TypeScript + Vite Boilerplate

This boilerplate template should help you get started with developing Vue 3 applications using TypeScript and Vite. The template also supports Sass. Vue 3 `<script setup>` SFCs are used in this template, for more information please refer to the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup).

## Getting Started

To get started with this boilerplate, follow these steps:

1. Clone the repository by running `git clone https://github.com/Don1k1337/vue-ts-boilerplate.git` in your terminal or use it as a template to create a new repository.
2. Install the dependencies by running `npm install` or `yarn` in the project directory.
3. Start the development server by running `npm run dev` or `yarn dev`.
4. Open a browser and navigate to `http://localhost:5173` to view the application. You can also change the default port in the `package.json` file by adding `--port=YOUR_PORT` to the `scripts` object `dev` line or in `vite.config.ts` by adding the following object: `server: { port: YOUR_PORT }`.

## Recommended IDE Setup

I  recommend using one of the following IDEs for developing your Vue 3 application:

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).
- [WebStorm](https://www.jetbrains.com/webstorm/) which supports the TypeScript compiler by default.

Choose the IDE that best suits your needs and preferences.

## Type Support For `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default. To solve this, we replace the `tsc` CLI with `vue-tsc` for type checking. Additionally, we need the [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) in editors to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. Follow the below steps to enable it:

1. Disable the built-in TypeScript Extension
   1. Run `Extensions: Show Built-in Extensions` from VSCode's command palette
   2. Find `TypeScript and JavaScript Language Features`, right-click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

Once you have set up the project, you can start developing your Vue 3 application by editing the files in the `src` directory.
