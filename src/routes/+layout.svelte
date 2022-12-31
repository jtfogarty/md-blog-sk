<script>
    import splitpanes from 'svelte-splitpanes';

let Splitpanes = splitpanes;
</script>

{#if Splitpanes}
	<svelte:self this={Splitpanes} />
{/if}

<Splitpanes>
	<div>Pane 1</div>
	<div><slot /></div>
</Splitpanes>
