<script>
  let user = { loggedIn: false };

  function toggle() {
    user.loggedIn = !user.loggedIn;
  }
</script>

{#if user.loggedIn}
  <button on:click={toggle}> Hello </button>
{:else}
  <button on:click={toggle}> Bye bye </button>
{/if}
