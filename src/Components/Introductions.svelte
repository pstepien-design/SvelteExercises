<script>
  import Nested from './Nested.svelte';
  let name = 'Paweł';
  let src = 'https://c.tenor.com/4gPD1ccxrVgAAAAC/rick-ashley-dance.gif';
  let nameOfArtis = 'Rick Astley';
  let string = `here we have some <strong>HTML!!!</strong>`;
</script>

<h1>Hello {name}!</h1>
<img {src} alt="{nameOfArtis} dancing" />
<p>Let's play with styles</p>
<Nested />
<p>{@html string}</p>

<style>
  p {
    color: purple;
    font-size: 2em;
  }
</style>
