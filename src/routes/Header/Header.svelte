<script>
    import NewsTicker from "../NewsTicker.svelte";
    const NewsItems = [
        "This is a recreation from the Pudding Article: When Women Make Headlines",
        "This is a recreation from the Pudding Article: When Women Make Headlines",
        "This is a recreation from the Pudding Article: When Women Make Headlines",
        "This is a recreation from the Pudding Article: When Women Make Headlines",
    ];
</script>

<header>
    <div class="contain">
        <a
            href="https://pudding.cool/2022/02/women-in-headlines/"
            target="_blank"><h1 class="Pudding">The Recreation</h1></a
        >
    </div>
    <div class="news">
        <NewsTicker items={NewsItems} />
    </div>
</header>

<style>
    header {
        display: flex;
    }

    .contain {
        width: auto;
        display: flex;
        justify-content: center;
        position: relative;
        background-color: rgb(247, 220, 91);
        transform: matrix(1, 0, -0.176327, 1, 0, 0);
        height: 48px;
        border-right: 1px solid rgb(40, 40, 40);
        max-width: 220px;
        position: absolute;
        z-index: 1000;
        top: 0px;
        bottom: -48px;
        right: -20px;
        left: -16px;
    }

    .Pudding {
        font-size: 24px;
        font-family: "Outfit", sans-serif;
        font-optical-sizing: auto;
        font-weight: 900;
        font-style: normal;
        letter-spacing: -0.02em;
        color: rgb(40, 40, 40);
        text-align: center;
        text-decoration: none;
        transform: matrix(1, 0, +0.176327, 1, 0, 0);
        padding: 5px 0px 0px 10px;
    }

    .news {
        width: 100%;
    }
</style>
