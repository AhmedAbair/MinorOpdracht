<script>
	export let x = 0;
</script>

<style>
	.ship {
		fill: #FF6347;
		stroke: #000;
		stroke-width: 1;
	}
	.sail {
		fill: #FFA07A;
	}
	.window {
		fill: #FFF;
		stroke: #000;
		stroke-width: 0.5;
	}
</style>

<svg viewBox="0 0 50 30" x="{x}" y="65" width="50" height="30">
	<polygon points="0,30 25,10 50,30" class="sail" />
	<rect x="10" y="20" width="30" height="10" class="ship" />
	<circle cx="20" cy="25" r="2" class="window" />
	<circle cx="30" cy="25" r="2" class="window" />
</svg>
