- I thought it was easier for you to copy/paste the file (or its content) rather than having to download the whole project. Hope it's fine.

- Despites being the last file called in `index.scss`, my custom rules in `custom.css` are not compiled in the same order on the React app. Therefore, `custom.css` content is called _before_ the app's styles in the compiled HTML. I had to give more specificity to my rules by prefixing them with `#root` in order to override app's styles :-/

- I chose to let the variable `--lumx-typography-font-family` do its job despites the Figma is using a Roboto font-face

- I didn't do anything about the « Load More » button because nothing was obvious about its styling (no Figma) or its overriding (no specific class)
