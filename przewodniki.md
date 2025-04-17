---
layout: default
title: Przewodniki
permalink: /plany/przewodniki.html
---

<div class="container">
  <aside>
    <h2>Przewodniki</h2>
    <ul>
      <li class="has-submenu">
        <a href="#" onclick="toggleSubmenu(event)">🇮🇹 Włochy ▼</a>
        <ul class="submenu">
          <li><a href="/plany/rzym.html">Rzym</a></li>
          <li><a href="/plany/neapol.html">Neapol</a></li>
          <!-- Dodaj więcej miast według potrzeb -->
        </ul>
      </li>
      <li class="has-submenu">
        <a href="#" onclick="toggleSubmenu(event)">🇪🇸 Hiszpania ▼</a>
        <ul class="submenu">
          <li><a href="/plany/madryt.html">Madryt</a></li>
          <li><a href="/plany/barcelona.html">Barcelona</a></li>
        </ul>
      </li>
      <!-- Możesz dodać kolejne kraje i miasta -->
    </ul>
  </aside>

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
