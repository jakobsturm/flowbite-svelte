---
layout: spinnerLayout
---

<script>
  import { Rating, Spinner, Table, TableDefaultRow }from '$lib/index';
  import componentProps from '../props/Rating.json'
  // Props table
  export let items = componentProps.props
	let propHeader = ['Name', 'Type', 'Default']
	// console.log(items)
	let divClass='w-full relative overflow-x-auto shadow-md sm:rounded-lg'
</script>

<h1 class="text-3xl w-full dark:text-white pt-16">Rating</h1>


```html
<script>
  import { Rating } from "flowbite-svelte";
</script>
```

<h2 class="text-2xl mt-8 dark:text-white py-8">Default</h2>

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <Rating stars={4} />
</div>

```html
  <Rating stars={4} />
```

<h2 class="text-2xl mt-8 dark:text-white py-8">With Text</h2>

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <Rating stars={4} type="text" text="4.95 out of 5" />
</div>

```html
  <Rating stars={4} type="text" text="4.95 out of 5" />
```

<h2 class="text-2xl mt-8 dark:text-white py-8">Rating count</h2>

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <Rating stars={4} type="count" text="4.95 out of 5" textUrl="https://flowbite.com/" />
</div>

```html
  <Rating 
    stars={4} 
    type="count" 
    text="4.95 out of 5" 
    textUrl="https://flowbite.com/" 
  />
```

<h2 class="text-2xl w-full dark:text-white py-8">Props</h2>

<p class="dark:text-white py-4 text-lg">The component has the following props, type, and default values. See <a href="/type-list" class="text-blue-600 hover:underline dark:text-blue-500">type-list page</a> for type information.</p>

<Table header={propHeader} {divClass} >
  <TableDefaultRow {items} rowState='hover' />
</Table>