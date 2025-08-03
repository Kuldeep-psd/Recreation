<!-- stacked chart -->
<div>
    <div id="observablehq-c1b-c273ec3a"></div>
    <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css"
    />
    <script type="module">
        import {
            Runtime,
            Inspector,
        } from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
        import define from "https://api.observablehq.com/d/30a84ebdc808c7ff@1424.js?v=4";
        new Runtime().module(define, (name) => {
            if (name === "c1b")
                return new Inspector(
                    document.querySelector("#observablehq-c1b-c273ec3a"),
                );
        });
    </script>
<style>

</style>
</div>
