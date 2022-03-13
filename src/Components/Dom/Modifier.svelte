<script>
  function handleClick() {
    alert('You could only click me once!');
  }
</script>

<button on:click|once={handleClick}> Try me </button>
