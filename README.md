# SVELTE-FLOW

## Installation

Install SvelteKit and TailwindCSS:

```sh
npm init svelte@next sveltekit-demo
cd sveltekit-demo
npm install
npx svelte-add@latest tailwindcss
```

Install Flowbite:

```sh
npm i flowbite
```

Add the following to the __layout.svelte:

```html
<script>
  import "../app.css";
  import "flowbite/dist/flowbite.css";
</script>
<div class="mx-auto p-2">
  <slot />
</div>
```

In `src/app.html`:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="description" content="" />
    <link rel="icon" href="%svelte.assets%/favicon.png" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
   
  %svelte.head%
  </head>
  <body>
    <div id="svelte">%svelte.body%</div>
    
    <script src="/node_modules/flowbite/dist/flowbite.js"></script>
  </body>
</html>
```

Install `flowbite-svelte`:

```sh
npm i -D flowbite-svelte
```
