---
layout: default
title: Przewodniki
permalink: /przewodniki.html
---

<div class="container">

  <main>
    <h1>Przewodniki</h1>
    <p>Wybierz kraj po lewej stronie, aby zobaczyć dostępne miasta i przewodniki turystyczne.</p>
  </main>
</div>

<script>
  function toggleSubmenu(event) {
    event.preventDefault();
    const item = event.target.closest('.has-submenu');
    item.classList.toggle('active');
  }
</script>
