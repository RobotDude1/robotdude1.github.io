<!doctype html>
<html lang="no">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Hei! Jeg er [Navnet ditt]</title>
    <style>
      body { font-family: system-ui, sans-serif; max-width: 720px; margin: 4rem auto; padding: 0 1rem; line-height: 1.6; }
      nav a { margin-right: 1rem; }
      h1 { margin-bottom: .25rem; }
      .muted { color: #666; }
      footer { margin-top: 3rem; font-size: .9rem; color: #666; }
    </style>
  </head>
  <body>
    <nav>
      <a href="/">Hjem</a>
      <a href="#prosjekter">Prosjekter</a>
      <a href="#kontakt">Kontakt</a>
    </nav>

    <h1>Hei, jeg er [Navn]</h1>
    <p class="muted">Utvikler / student / [din ting]. Dette er min lille krok på nettet.</p>

    <h2 id="prosjekter">Prosjekter</h2>
    <ul>
      <li><a href="https://github.com/brukernavn/prosjekt1">Prosjekt 1</a> – kort beskrivelse.</li>
      <li><a href="https://github.com/brukernavn/prosjekt2">Prosjekt 2</a> – kort beskrivelse.</li>
    </ul>

    <h2 id="kontakt">Kontakt</h2>
    <p>Finn meg på <a href="https://github.com/brukernavn">GitHub</a> eller send e-post: navn@domene.no</p>

    <footer>© <span id="y"></span> [Navn].</footer>
    <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
  </body>
</html>
