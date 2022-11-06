<script>
	let user = { darkMode: false };

	function toggle() {
		window.document.body.classList.toggle('dark-mode')	
		user.darkMode = !user.darkMode;
	}
	
</script>

{#if user.darkMode}
	<button on:click={toggle}>
		Dark  &#x1F31B
	</button>

{/if}


{#if !user.darkMode}
	<button on:click={toggle}>
		Light  &#x1F31E		
	</button>

{/if}
<style>
	button {
		background-color: #f76027;
		color: white;
		border: none;
		border-radius: 4px;
		padding: 0.5rem;
		text-transform: uppercase;
		position: fixed;
		z-index: 1;
		
	}
	:global(body.dark-mode) button {
		background-color: #0084f6;
		color: white;
	}
</style>
