<script>
  let cities = [
    { id: '1', name: 'Copenahegn' },
    { id: '2', name: 'Aarhus' },
    { id: '3', name: 'Odense' },
  ];
</script>

<h1>Biggest cities in Denmark</h1>
<ul>
  {#each cities as { name }, i}
    <li>
      {i + 1}: {name}
    </li>
  {/each}
</ul>
