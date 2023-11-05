<script lang="ts">
	import '../app.css';
</script>

<div class="flex flex-col min-h-dynamic-screen">
	<nav />
	<main class="flex-grow flex flex-col items-center gap-4 mx-1/16">
		<slot />
	</main>
	<footer />
</div>

<style>
	.min-h-dynamic-screen {
		min-height: 100dvh;
	}
</style>
