<script>
  import Info from './Info.svelte';

  const pkg = {
    date: '13.03.2022',
    city: 'Copenhagen',
    time: '17:45',
    weather: '8 degrees Celsius',
  };
</script>

<Info {...pkg} />
