# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).



- Creo il mio progetto vite da terminale con il comando: npm create vite@latest NOME_PROGETTO -- --template vue
 - Entro nella cartella del progetto con vscode o con il terminale
 - Eseguo il comando npm install
 - Rimuovo le componenti base che crea vue e faccio il primo push
 - Eseguo i comandi per installare i pacchetti
 - Installo Axios 'npm install axios'
 - installo sass 'npm add -D sass'
 - Installo Boostrap
 - Creo la cartella styles e dentro inserisco la cartella ' generals.scss '
 - Creo il file 'store.js' nella cartella 'src' con ' import { reactive } from 'vue'; ' e anche
  export const store = reactive({
  })
 - Creo la cartella 'styles' dentro 'src'
 - Creo la cartella 'partials' dentro 'styles' e gli applico il nome '_variables.scss'
 - Inserisco dentro la cartella partials anche il file '_mixins.scss'
 - Eseguo il comando npm run dev
 - Controllare che nello style ci sia lang='scss'
 - Creare la nuova componente