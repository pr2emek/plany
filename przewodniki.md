<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Przewodniki</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .container {
      display: flex;
      min-height: 100vh;
    }

    aside {
      width: 250px;
      background-color: #f2f2f2;
      padding: 20px;
      box-shadow: 2px 0 5px rgba(0,0,0,0.1);
    }

    aside h2 {
      font-size: 1.2rem;
      margin-bottom: 1rem;
    }

    aside ul {
      list-style: none;
      padding-left: 0;
    }

    aside ul li {
      margin-bottom: 10px;
    }

    aside ul li a {
      text-decoration: none;
      color: #333;
    }

    .has-submenu .submenu {
      display: none;
      list-style: none;
      padding-left: 15px;
      margin-top: 5px;
    }

    .has-submenu.active .submenu {
      display: block;
    }

    main {
      flex: 1;
      padding: 40px;
    }

    header, footer {
      padding: 20px;
      background-color: #fff;
      border-bottom: 1px solid #ccc;
      text-align: center;
    }

    footer {
      border-top: 1px solid #ccc;
    }

    nav ul.top-menu {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 1rem;
    }

    nav ul.top-menu li a {
      text-decoration: none;
      font-weight: bold;
      color: #444;
    }

    nav ul.top-menu li a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Plan podróży</h1>
    <p>Twoje przewodniki po Europie</p>
    <nav>
      <ul class="top-menu">
        <li><a href="/index.html">Start</a></li>
        <li><a href="/przewodniki.html">Przewodniki</a></li>
        <li><a href="/kontakt.html">Kontakt</a></li>
      </ul>
    </nav>
  </header>

  <div class="container">
    <aside>
      <h2>Przewodniki</h2>
      <ul>
        <li class="has-submenu">
          <a href="#" onclick="toggleSubmenu(event)">🇮🇹 Włochy ▼</a>
          <ul class="submenu">
            <li><a href="/rzym.html">Rzym</a></li>
            <li><a href="/neapol.html">Neapol</a
