---

layout: default
title: sitemap
permalink: /sitemap/
mermaid: true
---
# sitemap

Got lost? No worries, you can find everything right here.

<script src="https://unpkg.com/mermaid@9.2.2/dist/mermaid.min.js"></script>
<center>
<div class="mermaid">
flowchart TD;
    classDef className fill:#19A2A5,color:white,stroke-width:0px;
    id1([home])-->id2([research]);
    id1-->id3([about]);
    id1-->id4([Resume/CV]);
    id1-->id5([contact]);
    class id1,id2,id3,id4,id5 className;

    click id1 "/";
    click id2 "/research";
    click id3 "/about";
    click id4 "/CV";
    click id5 "/contact";
</div>
</center>
