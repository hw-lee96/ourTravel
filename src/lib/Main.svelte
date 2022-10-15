<script>
    import { push } from "svelte-spa-router";
</script>

<main>
    <h1>Our Travel</h1>
    <div class="btn">
        <button on:click={() => push("/counter")}>Go Counter</button>
    </div>
</main>