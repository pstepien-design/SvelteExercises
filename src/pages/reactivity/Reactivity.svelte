<script>
  import Assingments from '../../Components/Reactivity/Assignments.svelte';
  import Declarations from '../../Components/Reactivity/Declarations.svelte';
  import Statments from '../../Components/Reactivity/Statments.svelte';
</script>

<main>
  <h1>Hello reactivity!</h1>
  <Assingments />
  <Declarations />
  <Statments />
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
