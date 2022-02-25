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
  import { Alert } from "flowbite-svelte";
</script>
```

<h2 class="text-2xl w-full text-gray-900 dark:text-white">Alert Default Props</h2>

```js
let color = "blue"; // gray | red | yellow | green | indigo | purple | pink 
let alertId = "alert-1";
let closeBtn = false;
```

<h1 class="text-3xl w-full text-gray-900 dark:text-white my-8">Simple Alert Examples</h1>

```svelte
<Alert alertId="alert-blue">
    A simple info alert without a close button.
</Alert>

<Alert alertId="alert-gray" color="gray" closeBtn="true">
  A simple info alert with a close button.
</Alert>

<Alert alertId="alert-green" color="green" closeBtn="true">
  A simple info alert with a close button.
</Alert>

<Alert alertId="alert-red" color="red" closeBtn="true">
  A simple info alert with a close button.
</Alert>

<Alert alertId="alert-purple" color="purple" closeBtn="true">
  A simple info alert with a close button.
</Alert>

<Alert alertId="alert-yellow" color="yellow" closeBtn="true">
  A simple info alert with a close button.
</Alert>

<Alert alertId="alert-indigo" color="indigo" closeBtn="true">
  A simple info alert with a close button.
</Alert>

<Alert alertId="alert-pink" color="pink" closeBtn="true">
  A simple info alert with a close button.
</Alert>
```

<div class="rounded-xl w-full my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <Alert alertId="alert-blue">
    A simple info alert without a close button.
  </Alert>

  <Alert alertId="alert-gray" color="gray" closeBtn="true">
    A simple info alert with a close button.
  </Alert>

  <Alert alertId="alert-green" color="green" closeBtn="true">
    A simple info alert with a close button.
  </Alert>

  <Alert alertId="alert-red" color="red" closeBtn="true">
    A simple info alert with a close button.
  </Alert>

  <Alert alertId="alert-purple" color="purple" closeBtn="true">
    A simple info alert with a close button.
  </Alert>

  <Alert alertId="alert-yellow" color="yellow" closeBtn="true">
    A simple info alert with a close button.
  </Alert>

  <Alert alertId="alert-indigo" color="indigo" closeBtn="true">
    A simple info alert with a close button.
  </Alert>

  <Alert alertId="alert-pink" color="pink" closeBtn="true">
    A simple info alert with a close button.
  </Alert>
</div>
