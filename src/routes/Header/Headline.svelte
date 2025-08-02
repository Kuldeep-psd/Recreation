<section class="box">
    <div class="headline-box">
        <div>
            <h2 class="headline">WHEN</h2>
            <h2 class="headline">WOMEN</h2>
            <h2 class="headline">MAKE</h2>
            <h2 class="headline2">HEADLINES</h2>
        </div>
    </div>

    <div class="sidebar">
        <div class="contain">
            <p class="subtitle">
                A visual essay about the (mis)representation of women in the
                news
            </p>
            <p class="description">
                By <a
                    class="author"
                    href="https://pudding.cool/author/leonardo-nicoletti/"
                    >LEONARDO NICOLETTI</a
                >
                <br />and
                <a
                    class="author"
                    href="https://pudding.cool/author/sahiti-sarva/"
                    >SAHITI SARVA</a
                >
            </p>
        </div>
    </div>
</section>

<style>
    .box {
        display: flex;
        background-color: #fdf8f0;
        border-bottom: 1px solid #282828;
        width: auto;
        padding-top: 30px;
        margin-bottom: 80px;
    }

    .headline-box {
        padding-top: 20px;
        width: 70%;
    }

    .sidebar {
        border-left: 1px solid #282828;
        margin-left: -9px;
        display: flex;
        vertical-align: middle;
        width: calc(30% - 3rem);
        padding: 10rem 1.5rem;
    }

    .headline {
        font-family: "Barlow Condensed";
        text-transform: uppercase;
        font-style: italic;
        color: #282828;
        width: auto;
        display: block;
        font-size: 130px;
        padding-top: 20px;
        line-height: 0.8;
        font-weight: 900;
        border-bottom: 1px solid rgb(40, 40, 40);
        padding-left: 50px;
        transform: matrix(1, 0, -0.14, 1, 0, 0);
    }

    .headline2 {
        font-family: "Barlow Condensed";
        text-transform: uppercase;
        font-style: italic;
        color: #282828;
        width: auto;
        display: block;
        font-size: 130px;
        padding-top: 22px;
        line-height: 0.8;
        font-weight: 900;
        padding-left: 50px;
        transform: matrix(1, 0, -0.14, 1, 0, 0);
    }

    .author {
        font-family: "Barlow Condensed";
        font-weight: 700;
        color: #282828;
        text-decoration: underline;
        text-underline-offset: 3px;
    }

    .author:hover {
        text-decoration-color: #e76b2d;
    }

    .contain {
        display: block;
    }

    .subtitle {
        font-weight: 200;
        font-size: 24px;
        font-family: "Barlow Condensed";
        text-transform: uppercase;
        line-height: 1.4;
        font-weight: 300;
    }

    .description {
        margin-top: 20px;
        font-family: "Barlow Condensed";
        font-size: 16px;
        font-style: uppercase;
    }
</style>
