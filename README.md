# blank-vite-dark

This is a minimal React site created with Vite.

- TypeScript
- Sass
- only one Sass file (`App.scss`) - the file `index.css` was deleted
- page-load flicker bug fixed in index.html:
```
  <style>
    body {
      background-color: #333;
    }
  </style>
```

## install

- download zip
- copy all files to new directory, e.g. `/home/yourname/projects/site001`
- open VSCode in that directory (`code .`)
- `npm i`
- `npm run dev`
