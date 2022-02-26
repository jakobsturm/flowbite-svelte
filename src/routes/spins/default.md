---
layout: doc
---

<script>
  import { Spinner, SpinnerButton } from "flowbite-svelte";
</script>

<h1 class="text-3xl w-full dark:text-white">Spin</h1>


```svelte
<script>
  import { Spinner, SpinnerButton } from "flowbite-svelte";
</script>
```

<Spinner color="red" size="w-10 h-10" />
<Spinner color="yellow" align="text-center" />
<Spinner color="purple" align="text-right" />
<Spinner color="pink" align="text-left" />

<SpinnerButton color="blue" />
<SpinnerButton>Hang on there ...</SpinnerButton>


<h2 class="text-lg mt-8 dark:text-white">Colors</h2>

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<Spinner />
<Spinner color="green" />
</div>

```svelte
<Spinner />
<Spinner color="green" />
```



<h2 class="text-lg mt-8 dark:text-white">Text Size text-sm</h2>

```svelte
<Navbar textsize="text-sm" />
```

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<Navbar textsize="text-sm" />
</div>

<h2 class="text-lg mt-8 dark:text-white">Text Size text-base</h2>

```svelte
<Navbar textsize="text-base" />
```

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<Navbar textsize="text-base" />
</div>

<h2 class="text-lg mt-8 dark:text-white">Text Size text-lg</h2>

```svelte
<Navbar textsize="text-lg" />
```

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<Navbar textsize="text-lg" />
</div>

<h2 class="text-lg mt-8 dark:text-white">Text Size text-xl</h2>

```svelte
<Navbar textsize="text-xl" />
```

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<Navbar textsize="text-xl" />
</div>