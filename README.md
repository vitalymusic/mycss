🧑‍🏫 Pamācība: Kā izmantot savu CSS ietvaru mini.css
Šis ietvars ir izveidots, lai tu varētu ātri veidot tīmekļa lapas ar sakārtotu dizainu, bez nepieciešamības rakstīt CSS no nulles.

📁 1. Sagatavo mapi
Izveido projekta mapi, piemēram:

pgsql
Copy
Edit
mans-projekts/
├── index.html
└── mini.css
📝 2. HTML struktūra
Failā index.html izveido pamatstruktūru:

html
Copy
Edit
<!DOCTYPE html>
<html lang="lv">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mans projekts</title>
  <link rel="stylesheet" href="mini.css">
</head>
<body>

  <header>
    <h1>Laipni lūdzam!</h1>
  </header>

  <nav>
    <a href="#">Sākums</a>
    <a href="#">Par mums</a>
    <a href="#">Kontakti</a>
  </nav>

  <main>
    <section>
      <h2>Par šo vietni</h2>
      <p>Šeit mēs mācamies HTML un CSS pamatus.</p>
    </section>

    <article>
      <h3>Raksts</h3>
      <p>Raksta saturs ar formatētu tekstu, attēlu un citātu.</p>
      <blockquote>Tas, kurš mācās, kļūst gudrāks.</blockquote>
    </article>

    <form>
      <fieldset>
        <legend>Reģistrācija</legend>
        <label for="name">Vārds</label>
        <input type="text" id="name" required>

        <label for="email">E-pasts</label>
        <input type="email" id="email" required>

        <label for="password">Parole</label>
        <input type="password" id="password">

        <label><input type="checkbox"> Es piekrītu noteikumiem</label>

        <label class="switch">
          <input type="checkbox">
          <span class="slider"></span>
        </label>

        <button type="submit">Reģistrēties</button>
      </fieldset>
    </form>
  </main>

  <footer>
    <p>&copy; 2025 Mana lapa</p>
  </footer>

</body>
</html>
🧰 3. Ko šis ietvars dod?
✅ Skaisti formatēti:

Teksti, virsraksti, saraksti

Galvenes, navigācijas, kājenes

Formas elementi (ievades lauki, pogas, pārslēgi u.c.)

Tabulas, attēli, blokcitāti

Flexbox klases (.flex, .justify-center, .items-center u.c.)

🛠️ 4. Flexbox piemērs
html
Copy
Edit
<div class="flex justify-between items-center">
  <div>Pa kreisi</div>
  <div>Pa labi</div>
</div>
🎨 5. Pogas ar krāsām
html
Copy
Edit
<button class="btn-primary">Galvenā</button>
<button class="btn-success">Apstiprināt</button>
<button class="btn-danger">Dzēst</button>
🎯 Nobeigumā
Tu vari pilnībā fokusēties uz HTML struktūru un saturu — dizains jau ir gatavs!
