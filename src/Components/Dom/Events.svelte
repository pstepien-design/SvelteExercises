<script>
	let mousePosition = { x: 0, y: 0 };

	function handleMousemove(event) {
		mousePosition.x = event.clientX;
		mousePosition.y = event.clientY;
	}
</script>

<div on:mousemove={handleMousemove}>
	The mouse position is {mousePosition.x} x {mousePosition.y}
</div>

<style>
	div { width: 100%; height: 100%; }
</style>