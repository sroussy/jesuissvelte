<script>
    export let name;
</script>

<main>
    <h1>Is it you {name}<span class="spaceBefore">?!</span></h1>
    <p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style>
    main {
        text-align: center;
        padding: 1em;
        max-width: 240px;
        margin: 0 auto;
    }

    h1 {
        /*color: #ff3e00;*/
        color: #ff0057;
        text-transform: uppercase;
        font-size: 4em;
        font-weight: bold;
    }

    .spaceBefore{
        margin-left: 0.2em;
    }

    @media (min-width: 640px) {
        main {
            max-width: none;
        }
    }
</style>