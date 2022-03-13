<script>
  let count = 1;

  $: doubled = count * 2;
  $: tripled = count * 3;
  $: quadrapled = count * 4;
  function handleClick() {
    ++count;
  }
</script>

<button on:click={handleClick}>
  Count: {count}
</button>

<p>{count} * 2 = {doubled}</p>
<p>{count} * 3 = {tripled}</p>
<p>{count} * 4 = {quadrapled}</p>

<style>
  button {
    border-radius: 3px;
    background-color: pink;
    width: 50%;
  }
</style>
