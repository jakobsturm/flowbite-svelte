<script lang="ts">
	import type { CardButtonType, Colors } from '../types';
	import Button from '../buttons/Button.svelte';
	export let title: string = 'Work fast from anywhere';
	export let headColor: Colors = 'gray';
	export let btns: CardButtonType[];
	export let divClass: string = 'p-4 w-full text-center bg-white rounded-lg border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700';
	let headClass: string;
	if (headColor === 'blue') {
		headClass = 'mb-2 text-3xl font-bold text-blue-900 dark:text-white';
	} else if (headColor === 'gray') {
		headClass = 'mb-2 text-3xl font-bold text-gray-900 dark:text-white';
	} else if (headColor === 'red') {
		headClass = 'mb-2 text-3xl font-bold text-red-900 dark:text-white';
	} else if (headColor === 'yellow') {
		headClass = 'mb-2 text-3xl font-bold text-yellow-900 dark:text-white';
	} else if (headColor === 'green') {
		headClass = 'mb-2 text-3xl font-bold text-green-900 dark:text-white';
	} else if (headColor === 'indigo') {
		headClass = 'mb-2 text-3xl font-bold text-indigo-900 dark:text-white';
	} else if (headColor === 'purple') {
		headClass = 'mb-2 text-3xl font-bold text-purple-900 dark:text-white';
	} else if (headColor === 'pink') {
		headClass = 'mb-2 text-3xl font-bold text-pink-900 dark:text-white';
	} else {
		headClass = 'mb-2 text-3xl font-bold text-blue-900 dark:text-white';
	}
</script>

<div class={divClass}>
	<h3 class={headClass}>
		{title}
	</h3>
	<p class="mb-5 text-base text-gray-500 sm:text-lg dark:text-gray-400">
		<slot />
	</p>
	<div class="justify-center items-center space-y-4 sm:flex sm:space-y-0 sm:space-x-4">
		{#if btns}
			{#each btns as { name, textSize, type, href, rel, rounded }}
				<a {href} {rel}>
					<Button {name} {rounded} {type} {textSize} />
				</a>
			{/each}
		{/if}
	</div>
</div>
