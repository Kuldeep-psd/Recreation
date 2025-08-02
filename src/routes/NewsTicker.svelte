<script>
    /**
     * @type {string[]}
     */
    export let items = [];
</script>

<div class="ticker-container">
        <div class="ticker-track">
            {#each items as item}
                <div class="ticker-item">{item}</div>
            {/each}
            {#each items as item}
                <div class="ticker-item">{item}</div>
            {/each}
        </div>
</div>

<style>
    .ticker-container {
        overflow: hidden;
        height: 100%;
        display: flex;
        background-color: #e76b2d;
        padding: 7px 0;
        height: 3rem;
        position: absolute;
        -webkit-box-align: center;
        align-items: center;
        width: 100%
    }

    .ticker-track {
        white-space: nowrap;
        animation: scroll-left 25s linear infinite;
        display: flex;
    }

    @keyframes scroll-left {
        0% {
            transform: translateX(0);
        }
        100% {
            transform: translateX(-50%);
        }
    }

    .ticker-item {
        padding: 0 2rem;
        font-family: "Barlow Condensed", sans-serif;
        font-weight: 300;
        font-style: italic;
        text-transform: uppercase;
        font-size: 22.5px;
        color: #282828;
        display: flex;
        transform: skewX(-10deg);
    }

    .ticker-item:not(:last-child)::after {
        content: '';
        position: absolute;
        right: 0;
        top: 50%;
        transform: translateY(-50%);
        width: 1px;
        height: 50%;
        display: flex;
    }
</style>