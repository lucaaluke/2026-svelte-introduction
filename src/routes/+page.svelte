<script>
    console.log("Hello World");
    let count = $state(0);
        let doubled = $derived(count * 2);
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<button onclick={() => count++}>
    Clicks: {count}
</button>

<span>Doubled: {doubled}</span>

<style>
    h1{
        color:deepskyblue;
    }

    a{
        color:forestgreen;
    }


</style>