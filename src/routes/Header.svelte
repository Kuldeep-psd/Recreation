<script>
    import NewsTicker from './NewsTicker.svelte';
    const NewsItems = [
        "This is a recreation from the Pudding Article: When Women Make Headlines",
        "This is a recreation from the Pudding Article: When Women Make Headlines",
        "This is a recreation from the Pudding Article: When Women Make Headlines",
        "This is a recreation from the Pudding Article: When Women Make Headlines"
    ];
</script>

<header>
    <div class="contain">
        <a href="https://pudding.cool/2022/02/women-in-headlines/" target="_blank"><h1 class="Pudding">The Recreation</h1></a>
    </div>
    <div class="news">
        <NewsTicker items={NewsItems}/>
    </div>
</header>

<style>
    :global(header){
        display: flex;
    }

    .contain {
        width: 100%;
        display: flex;
        justify-content: center;
        position: relative;
        background-color: rgb(247, 220, 91);
        transform: matrix(1, 0, -0.176327, 1, 0, 0);
        height: 48px;	
        width: 196px;
        border-right: 1px solid rgb(40, 40, 40);	
        max-width: 196px;	
        position: absolute;
        z-index: 1000;
        top: 0px;
             bottom: -48px;	right: -20px;	
        left: -16px;
    }

    .Pudding {
        font-family: "Barlow Condensed", sans-serif;	
        font-size: 20px;	
        font-weight: 600;
        color: rgb(40, 40, 40);
        text-align: center;
        text-transform: uppercase;
        text-decoration: none;
        
        }

    .news {
        width: 100%;
        }
</style>