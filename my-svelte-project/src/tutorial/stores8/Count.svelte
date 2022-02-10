<!--App.svelte 
    <script>
	import { count } from './stores.js';
	import Incrementer from './Incrementer.svelte';
	import Decrementer from './Decrementer.svelte';
	import Resetter from './Resetter.svelte';
</script>

<h1>The count is {$count}</h1>

<Incrementer/>
<Decrementer/>
<Resetter/> -->

<!-- Decrementer
    <script>
	import { count } from './stores.js';

	function decrement() {
		count.update(n => n - 1);
	}
</script>

<button on:click={decrement}>
	-
</button> -->

<!-- Incrementer
    <script>
	import { count } from './stores.js';

	function decrement() {
		count.update(n => n + 1);
	}
</script>

<button on:click={decrement}>
	-
</button> -->

<!-- Resseter
    <script>
	import { count } from './stores.js';

	function reset() {
		count.set(0);
	}
</script>

<button on:click={reset}>
	reset
</button> -->

<!-- stores.js
     import { writable } from 'svelte/store';

export const count = writable(0); -->
