---
layout: doc
---

<script>
  import { Spinner, SpinnerButton } from "flowbite-svelte";
</script>

<h1 class="text-3xl w-full dark:text-white">Spinner</h1>


```svelte
<script>
  import { Spinner, SpinnerButton } from "flowbite-svelte";
</script>
```

<h2 class="text-lg mt-8 dark:text-white">Colors</h2>

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<Spinner />
<Spinner color="green" />
<Spinner color="green" />
<Spinner color="green" />
<Spinner color="green" />
<Spinner color="green" />
<Spinner color="green" />
</div>

```svelte
<Spinner />
<Spinner color="green" />
```


<Spinner color="red" size="w-10 h-10" />
<Spinner color="yellow" align="text-center" />
<Spinner color="purple" align="text-right" />
<Spinner color="pink" align="text-left" />

<SpinnerButton color="blue" />
<SpinnerButton>Hang on there ...</SpinnerButton>


