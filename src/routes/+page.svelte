<script>
    import ClicksCounter from "$lib/components/ClicksCounter.svelte";
    import ProgressiveSum from "$lib/components/ProgressiveSum.svelte";
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<ClicksCounter />
<ProgressiveSum />

<style>
    h1{
        color:deepskyblue;
    }

    a{
        color:forestgreen;
    }


</style>