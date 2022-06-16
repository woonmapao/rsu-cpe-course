<script>
    import Button from "../components/Button.svelte";
    import Tree from "../components/Tree.svelte";
    import Grid from "../components/Grid.svelte";

    let mode = true;
    let innerWidth = 0;

    $: condition = innerWidth > 1870 && innerWidth < 1930;
</script>

<svelte:window bind:innerWidth />

<div class="container">
    <header
        class="d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-3 mb-4 border-bottom"
    >
        <a
            href="/"
            class="d-flex align-items-center col-md-3 mb-2 mb-md-0 text-dark text-decoration-none"
        >
            <img src="images/cpe.png" alt="CPE_LOGO" height="50" />
            <h1>Home</h1>
        </a>

        <div
            class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0 fs-2"
        >
            ตัวจัดการวิชาเรียน CPE<br />
        </div>
    </header>
</div>
<!-- <button class="btn-main" on:click={() => (mode = !mode)}>เปลี่ยนโหมด</button> -->
<Button text="เปลี่ยนโหมด" on:click={() => (mode = !mode)} />

{#if condition}
    {#if mode}
        <Tree />
    {:else}
        <Grid />
    {/if}
{:else}
    <h3>So sorry</h3>
    <h2>Only support 1920 x 1080</h2>
{/if}

<style>
    header {
        padding: 8px 0;
    }

    h1 {
        color: #614124;
        margin: auto 0 auto 1rem;
    }

    .container {
        margin-bottom: 0;
        max-width: 60%;
    }
</style>
