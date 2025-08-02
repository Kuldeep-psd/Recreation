<!-- ridge chart -->
<div>
    <svg style="height: 0; width: 0;">
        <linearGradient id="areaGradient" x1="0%" y1="0%" x2="0%" y2="100%"
            ><stop offset="0%" stop-color="#f76e45"></stop><stop
                offset="90%"
                stop-color="#FEFAF1"
            ></stop><stop offset="100%" stop-color="#FEFAF1"
            ></stop></linearGradient
        >
    </svg>

    <div id="observablehq-c5-4b6a74de"></div>
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
            if (name === "c5")
                return new Inspector(
                    document.querySelector("#observablehq-c5-4b6a74de"),
                );
        });
    </script>
</div>
