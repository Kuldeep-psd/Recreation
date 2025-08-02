<!-- bubble chart 2 -->
<div>
    <div id="observablehq-c4b-f983bdaa"></div>
    <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css"
    />
    <script type="module">
        import {
            Runtime,
            Inspector,
        } from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
        import define from "https://api.observablehq.com/d/30a84ebdc808c7ff@792.js?v=4";
        new Runtime().module(define, (name) => {
            if (name === "c4b")
                return new Inspector(
                    document.querySelector("#observablehq-c4b-f983bdaa"),
                );
        });
    </script>
</div>
