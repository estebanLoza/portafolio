<script>
	export let name;
	let otroNombre = "esteban";
	
</script>

<main>
	<h1>Hello {name}!</h1>
	<h2>HELLO {otroNombre}</h2>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	 <p>ESTO ESTA ESCRITO DESDE TERMUX </p>
	  <ul>
	    <li>Esto es una lista de prueba</li>
	    <li>Esto es una lista de prueba</li>
	    <li>Esto es una lista de prueba</li>
	    <li>Esto es una lista de prueba</li>
	  </ul>
  
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>