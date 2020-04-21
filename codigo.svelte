<script>
	let h = new Date();
	let horas = h.getHours();

</script>

{#if horas < 5}
		<h1>Boa noite!!!</h1>
{:else}
	{#if horas < 8}
		<h1>Bom Dia!!!</h1>
{:else}
	{#if horas < 12}
		<h1>Bom Dia!!!</h1>
{:else}
	{#if horas < 18}
		<h1>Boa Tarde!!!</h1>
{:else}
	<h1>Boa Noite!!!</h1>
			{/if}
		{/if}
	{/if}
{/if}

<style>
h1{
	text-align: center;
	color: #ff3e00;
	text-transform: uppercase;
	font-size: 4em;
	font-weight: 100;
}
</style>