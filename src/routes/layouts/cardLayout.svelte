<script>
  import 'prism-themes/themes/prism-holi-theme.css';
  import { Utterances } from '@codewithshin/svelte-utterances';
</script>

<div class="max-w-3xl mx-auto pb-8">
  <div class="container flex flex-wrap mx-auto pt-8">
    <slot />
    <h2 class="text-2xl w-full dark:text-white pt-16 pb-8">Related components</h2>

    <p class="dark:text-white text-lg w-full">
      <a href="/cards/card" class="text-blue-600 hover:underline dark:text-blue-500">Default Card</a>
    </p>

    <p class="dark:text-white text-lg w-full">
      <a href="/cards/cta" class="text-blue-600 hover:underline dark:text-blue-500">CTA Card</a>
    </p>

    <p class="dark:text-white text-lg w-full">
      <a href="/cards/ecommerce" class="text-blue-600 hover:underline dark:text-blue-500">Ecommerce Card</a>
    </p>

    <p class="dark:text-white text-lg w-full">
      <a href="/cards/horizontal" class="text-blue-600 hover:underline dark:text-blue-500">Horizontal Card</a>
    </p>

    <p class="dark:text-white text-lg w-full">
      <a href="/cards/interactive" class="text-blue-600 hover:underline dark:text-blue-500">Interactive Card</a>
    </p>

    <p class="dark:text-white text-lg w-full">
      <a href="/cards/list" class="text-blue-600 hover:underline dark:text-blue-500">List Card</a>
    </p>

    <p class="dark:text-white text-lg w-full">
      <a href="/cards/signin" class="text-blue-600 hover:underline dark:text-blue-500">Signin Card</a>
    </p>

    <h2 class="text-2xl w-full dark:text-white pt-8 pb-4">References</h2>

    <p class="dark:text-white text-lg">
      <a href="https://flowbite.com/docs/components/card/" target="_blank" class="text-blue-600 hover:underline dark:text-blue-500">Flowbite Card</a>
    </p>
  </div>

  <div class="container my-16 mx-auto">
    <Utterances reponame="shinokada/flowbite-svelte" theme="dark-blue" />
  </div>
</div>
