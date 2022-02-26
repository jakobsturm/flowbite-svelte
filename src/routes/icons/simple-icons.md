---
layout: doc
---

<script>
   import { FacebookIcon, GithubIcon, GitIcon } from '@codewithshin/svelte-simpleicons';
</script>

<h1 class="text-3xl w-full dark:text-white mb-4">Simple-icons</h1>

<p class=" dark:text-white">Svelte-simpleicons has more than 2100 icons and they are mono-color icons.</p>


<h2 class="text-2xl w-full dark:text-white mt-8">Installing Simple-icons</h2>

```sh
npm i -D @codewithshin/svelte-simpleicons
```

<h2 class="text-2xl w-full dark:text-white mt-8">Examples</h2>

<div class="container flex flex-wrap justify-center rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6 h-72">

<FacebookIcon className="h-4 w-4 w-full" fill="#4287f5" />
<GithubIcon fill="#66f5fa" />  
<FacebookIcon className="h-8 w-8 w-full" fill="#02fa0b" />
<GithubIcon className="h-10 w-10 w-full" fill="#6e7070" />
<GitIcon className="h-12 w-12 w-full" fill="#bc02fa" />
<GitIcon className="h-24 w-24 w-full" fill="#fa0202" />

</div>

```svelte
<script>
import { FacebookIcon, GithubIcon, GitIcon } from '@codewithshin/svelte-simpleicons';
</script>

<FacebookIcon className="h-4 w-4 w-full" fill="#4287f5" />
<GithubIcon fill="#66f5fa" />  
<FacebookIcon className="h-8 w-8 w-full" fill="#02fa0b" />
<GithubIcon className="h-10 w-10 w-full" fill="#6e7070" />
<GitIcon className="h-12 w-12 w-full" fill="#bc02fa" />
<GitIcon className="h-24 w-24 w-full" fill="#fa0202" />

```

<h1 class="text-3xl w-full dark:text-white pb-8">References</h1>

<p class="w-full dark:text-white text-base"><a href="https://github.com/shinokada/svelte-simpleicons" target="_blank" class="text-blue-600 hover:underline dark:text-blue-500">- Svelte-simpleicons</a></p>

<p class="w-full dark:text-white text-base"><a href="https://simpleicons.org/" target="_blank" class="text-blue-600 hover:underline dark:text-blue-500">- Simple Icons</a></p>

