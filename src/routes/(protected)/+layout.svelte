<script lang="ts">
	import '../../app.css';

	let { children } = $props();
</script>

<div class="container">
	<main>
		{@render children()}
	</main>
	<footer>
		<p>
		</p>
	</footer>
</div>

<style>
	
</style>
