---
layout: default
---

<script>
    document.getElementsByClassName('site-title')[0].innerHTML = "<img src='/assets/sqlflow-logo.svg' style='height: 30px' />"
</script>

<style>
a {color: #1BA2FF}
</style>

{{content | replace: "/example/" , "/sqlflow/example/"| replace: "doc/figures/" , "/sqlflow/doc/figures/"}}


