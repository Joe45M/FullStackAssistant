<script>
    let counter = 0;

    function countUp() {
        counter = counter + 1;
    }
</script>

<h1>Welcome to SvelteKit</h1>
<button on:click={countUp}>{ counter }</button>
<a href="/about">about -changed</a>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
