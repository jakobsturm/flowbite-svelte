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
  import { InfoAlert } from "flowbite-svelte";
</script>
```


<h2 class="text-2xl w-full text-gray-900 dark:text-white">InfoAlert Default Props</h2>

```js
let color = "blue";
let alertId = "alert-additional-content-1";
let infoLink = false;
let closeBtn = false;
```

<h1 class="text-2xl w-full text-gray-900 dark:text-white my-8">Information Alert Examples</h1>

```svelte
<InfoAlert>
    <span slot="header">Info header 1</span>
    InfoAlert without View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-2"
    color="green"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 2</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-3"
    color="red"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 3</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-4"
    color="yellow"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 4</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-5"
    color="gray"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 5</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-6"
    color="indigo"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 4</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-7"
    color="purple"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 4</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-8"
    color="pink"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 4</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>
```

<div class="rounded-xl w-full my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">

  <InfoAlert>
    <span slot="header">Info header 1</span>
    InfoAlert without View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-2"
    color="green"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 2</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-3"
    color="red"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 3</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-4"
    color="yellow"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 4</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-5"
    color="gray"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 5</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-6"
    color="indigo"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 4</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-7"
    color="purple"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 4</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>

  <InfoAlert
    alertId="info-alert-8"
    color="pink"
    closeBtn="true"
    infoLink="/"
  >
    <span slot="header">Info header 4</span>
    InfoAlert with View more and Dismiss button.
  </InfoAlert>
</div>

