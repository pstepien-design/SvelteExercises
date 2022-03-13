<script>
	import { createEventDispatcher } from 'svelte';

	const dispatch = createEventDispatcher();

	function sayHello() {
		dispatch('message', {
			text: 'Welcome!!'
		});
	}
</script>

<button on:click={sayHello}>
	Click to say welcome
</button>