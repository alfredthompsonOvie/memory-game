# memory-game

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
Requirements
- Cards should be laid out on a 6x6 grid, all face down initially (i.e. numbers not showing)
- There should be a total of 36 cards with the numbers 1-18 (two of each), placed randomly on the grid
- Clicking a card should 'reveal' it - showing the hidden number of the card
- Clicking a second card should reveal that card
- If the second card has the same number as the first card, both cards should be removed from the board after 3 seconds
- If the second card has a different number to the first card, both cards should be 'hidden' again after 3 seconds (i.e. turned face down)
- The user shouldn't be able to turn over any more cards until the 3 second timer completes and the two revealed cards are either removed (if they matched), or hidden again (if they didn't)
- Once all cards are removed from the board, the game is over and the 'Play again' button should be shown
- Clicking 'Play again' should generate a new, random set of cards on the grid