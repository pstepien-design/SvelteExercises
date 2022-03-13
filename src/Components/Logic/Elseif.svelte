<script>
  let x = 0;

  function handleX() {
    ++x;
  }
</script>

<button on:click={handleX}>
  Clicked {x}
  {x === 1 ? 'time' : 'times'}</button
>

{#if x > 10}
  <p>{x} is greater than 10</p>
{:else if 5 > x}
  <p>{x} is less than 5</p>
{:else}
  <p>{x} is between 5 and 10</p>
{/if}
