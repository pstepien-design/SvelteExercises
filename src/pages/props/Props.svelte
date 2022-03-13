<script>
  import Declaring from '../../Components/Props/Declaring.svelte';
  import Spread from '../../Components/Props/Spread.svelte';
</script>

<main>
  <h1>Hello props!</h1>
  <Declaring />
  <Spread />
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
