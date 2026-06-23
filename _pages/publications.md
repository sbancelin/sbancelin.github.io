---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="d-flex align-items-center justify-content-between flex-wrap" style="gap: 0.75rem; margin-bottom: 1rem;">
  <span class="text-muted">Publications in reverse chronological order.</span>
  {% include bib_search.liquid %}
</div>

<div class="publications">

{% bibliography %}

</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    var green = (getComputedStyle(document.documentElement).getPropertyValue("--global-theme-color") || "#32cb32").trim();
    document.querySelectorAll(".publications a.btn").forEach(function (a) {
      var href = a.getAttribute("href") || "";
      if (href.indexOf("/assets/pdf/") === -1) return;
      a.style.color = green;
      a.style.borderColor = green;
      if (!a.querySelector("i.fa-file-pdf")) {
        var icon = document.createElement("i");
        icon.className = "fa-solid fa-file-pdf";
        icon.style.marginRight = "0.35em";
        a.insertBefore(icon, a.firstChild);
      }
    });
  });
</script>
