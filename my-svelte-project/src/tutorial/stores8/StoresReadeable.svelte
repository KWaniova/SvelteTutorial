<!--App.svelte 
     <script>
	import { time } from './stores.js';

	const formatter = new Intl.DateTimeFormat('en', {
		hour12: true,
		hour: 'numeric',
		minute: '2-digit',
		second: '2-digit'
	});
</script>

<h1>The time is {formatter.format($time)}</h1> -->

<!-- stores.js
     import { readable } from 'svelte/store';

export const time = readable(null, function start(set) {
const interval = setInterval(() => {
		set(new Date());
	}, 1000);
	return function stop() {
		clearInterval(interval);
	};
}); -->
