<script>
    export let text = "";
</script>

<button
    class="btn-main"
    on:click
    style="font-family: 'Kanit', 'Roboto', sans-serif;">{text}</button
>

<style>
    button {
        margin-bottom: 1rem;
    }

    .btn-main {
        appearance: none;
        background-color: #614124;
        border-radius: 40em;
        border-style: none;
        box-shadow: #3c2816 0 -12px 6px inset;
        box-sizing: border-box;
        color: #ffffff;
        cursor: pointer;
        display: inline-block;
        font-family: -apple-system, sans-serif;
        font-size: 1.2rem;
        font-weight: 700;
        letter-spacing: -0.24px;
        margin: 0;
        outline: none;
        padding: 1rem 1.3rem;
        quotes: auto;
        text-align: center;
        text-decoration: none;
        transition: all 0.15s;
        user-select: none;
        -webkit-user-select: none;
        touch-action: manipulation;
    }

    .btn-main:hover {
        background-color: #ffc229;
        box-shadow: #ff6314 0 -6px 8px inset;
        transform: scale(1.125);
    }

    .btn-main:active {
        transform: scale(1.025);
    }

    @media (min-width: 768px) {
        .btn-main {
            font-size: 1.5rem;
            padding: 0.75rem 2rem;
        }
    }
</style>
