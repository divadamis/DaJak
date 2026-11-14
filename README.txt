DaJak – PWA aplikace
====================

Obsah složky:
  index.html            hra
  manifest.webmanifest  název, barvy a ikony aplikace
  sw.js                 service worker (hra funguje i offline, aktualizace se načtou při dalším spuštění)
  icons/                ikony (192, 512, maskable pro Android, apple-touch-icon pro iPhone)

Zveřejnění (PWA musí běžet přes HTTPS):
  - Netlify Drop: přetáhni celou složku "dajak" na stránku app.netlify.com/drop – dostaneš https adresu.
  - nebo GitHub Pages: nahraj obsah složky do repozitáře a zapni Pages.
  - Soubory nahraj tak, jak jsou (index.html v kořeni, vedle něj sw.js a manifest).

Instalace do telefonu:
  - iPhone (Safari): otevři adresu › Sdílet › Přidat na plochu.
  - Android (Chrome): otevři adresu › nabídka ⋮ › Nainstalovat aplikaci (často se nabídne sama).

Aktualizace hry: nahraj nový index.html a v sw.js změň název verze (const V='dajak-…'),
aby si telefony stáhly novou verzi.
