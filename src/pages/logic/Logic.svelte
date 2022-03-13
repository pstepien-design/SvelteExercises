<script>
  import Ifblock from '../../Components/Logic/Ifblocks.svelte';
  import Else from '../../Components/Logic/Else.svelte';
  import ElseIf from '../../Components/Logic/Elseif.svelte';
  import Each from '../../Components/Logic/Each.svelte';
</script>

<main>
  <h1>Hello logic!</h1>
  <Ifblock />
  <Else />
  <ElseIf />
  <Each />
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
