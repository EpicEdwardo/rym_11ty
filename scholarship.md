---
layout: default-layout.njk
title: Scholarship
---

<div id="openseadragon1" style="width: 800px; height: 600px;"></div>

<script src="/assets/openseadragon/openseadragon.min.js"></script>
<script type="text/javascript">
    var viewer = OpenSeadragon({
        id: "openseadragon1",
        prefixUrl: "/assets/openseadragon/images/",
        tileSources: "/assets/mydz.dzi"
    });
</script>


