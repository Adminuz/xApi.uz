<script>
import Head from "./Component/Head.svelte";
import Project from './Component/Project/Index.svelte';
import Skills from './Component/Skills/Index.svelte'
</script>
<Head/>
<Skills/>
<Project/>
<main>
	<br/>
    <p>I ❤️ code. made by Admin_uz</p>
	<p>Company <a href="https://xapi.uz">xApi.Uz</a></p>
</main>
 


<style>

 :global(body){
	font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
	
    padding:0px;
    margin: 0px
   }
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}


	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}


</style>