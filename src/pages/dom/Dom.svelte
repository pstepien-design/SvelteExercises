<script>
  import Events from '../../Components/Dom/Events.svelte';
  import Inline from '../../Components/Dom/Inline.svelte';
  import Modifier from '../../Components/Dom/Modifier.svelte';
  import Inner from '../../Components/Dom/Inner.svelte';
  import Outer from '../../Components/Dom/Outer.svelte';
	function handleMessage(event) {
		alert(event.detail.text);
	}
</script>

<main>
  <h1>Hello logic!</h1>

  <Events />
  <Inline />
  <Modifier />
  <Inner  on:message={handleMessage} />
  <Outer  on:message={handleMessage} />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
