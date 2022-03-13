<script>
  import Introductions from './Components/Introductions.svelte';
  import Reactivity from './pages/reactivity/Reactivity.svelte';
  import Props from './pages/props/Props.svelte';
  import Logic from './pages/logic/Logic.svelte';
  import Dom from './pages/dom/Dom.svelte';
</script>

<main>
  <h1>Hello!</h1>
  <Introductions />
  <Reactivity />
  <Props />
  <Logic />
  <Dom />
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
