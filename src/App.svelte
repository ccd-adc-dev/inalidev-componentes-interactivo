<script>
	
	import IconoVoluta from "./componentes/Voluta/IconoVoluta.svelte";
	import IconoTwitterAzul from "./componentes/Twitter/Iconos/IconoTwitterAzul.svelte";
	import Informacion from "./componentes/Informacion/Informacion.svelte";
	import Twitter from "./componentes/Twitter/Twitter.svelte";
	import Tweet from "./componentes/Twitter/Tweet.svelte";

</script>

<style>
	* {
		outline: 1px solid blue;
	}
	
	 .Contenedor-1 {
		display: flex;
		flex-flow: row wrap;
		justify-content: space-between;
		align-content: space-between;
	}


</style>


<div class="Contenedor-1">
		
			<Informacion/>
			<Twitter/>
			<IconoTwitterAzul/>
			<IconoVoluta/>
		
		
</div>


		



