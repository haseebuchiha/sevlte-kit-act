<script>
 export let data
 console.log(data)
</script>
<!-- <svelte:head> -->
<!-- 	<title>About</title> -->
<!-- 	<meta name="description" content="About this app" /> -->
<!-- </svelte:head> -->

<div class="text-column">
	<h1>About this app</h1>
  <slot />
	<footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer>
</div>
