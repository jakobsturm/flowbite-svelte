---
layout: doc
---

<script>
  import { Alert, BorderAlert, InfoAlert } from "flowbite-svelte";
</script>

<h1 class="text-3xl w-full text-gray-900 dark:text-white my-8">Alert: Setup</h1>

<p class="text-gray-900 dark:text-white">
Import Alert, BorderAlert, and InfoAlert and set variables in the script tag.
</p>

```svelte
<script>
  import { BorderAlert } from "flowbite-svelte";
</script>
```

<h2 class="text-2xl w-full text-gray-900 dark:text-white">BorderAlert Default Props</h2>

```js
let color = "blue"; // gray | red | yellow | green | indigo | purple | pink 
let alertId = "alert-border-1";
let closeBtn = false;
```

<h1 class="text-2xl w-full text-gray-900 dark:text-white my-8">Border Alert Examples</h1>

```svelte
<BorderAlert color="blue">
  A border alert without the close button.
</BorderAlert>

<BorderAlert color="gray">
  A border alert without the close button.
</BorderAlert>

<BorderAlert color="green">
  A border alert without the close button.
</BorderAlert>

<BorderAlert alertId="border-alert-1" color="yellow" closeBtn="true">
  A border alert with the close button.
</BorderAlert>

<BorderAlert alertId="border-alert-2" color="red" closeBtn="true">
  A border alert with the close button.
</BorderAlert>
```

<div class="rounded-xl w-full my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <BorderAlert color="blue">
    A border alert without the close button.
  </BorderAlert>

  <BorderAlert color="gray">
    A border alert without the close button.
  </BorderAlert>

  <BorderAlert color="green">
    A border alert without the close button.
  </BorderAlert>

  <BorderAlert alertId="border-alert-1" color="yellow" closeBtn="true">
    A border alert with the close button.
  </BorderAlert>

  <BorderAlert alertId="border-alert-2" color="red" closeBtn="true">
    A border alert with the close button.
  </BorderAlert>
</div>

