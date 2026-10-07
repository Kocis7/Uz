# Plánovač – 4.A a Vnorovy

Osobní plánovač (rozvrh, úkoly, testy, zápasy, svátky, narozeniny) jako instalovatelná PWA appka.

## Nasazení na GitHub Pages (zdarma, bez příkazové řádky)

1. Na [github.com](https://github.com) založ nový repozitář (New repository) – klidně veřejný, název např. `planovac`.
2. V repozitáři klikni na **Add file → Upload files** a přetáhni tam všech pět souborů z této složky
   (`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`). Commit changes.
3. Jdi do **Settings → Pages**.
4. U "Build and deployment" vyber **Source: Deploy from a branch**, **Branch: main**, složka **/ (root)**. Save.
5. Za chvíli se nahoře objeví zelený odkaz typu `https://tvoje-jméno.github.io/planovac/` – to je tvoje appka.

## Instalace na iPhone

1. Otevři ten `github.io` odkaz v Safari.
2. Ikona sdílení (čtvereček se šipkou) → **Přidat na plochu** → Přidat.

## Poznámka k datům

Appka ukládá rozvrh, úkoly, zápasy a narozeniny do paměti prohlížeče (localStorage) na tom
konkrétním zařízení/prohlížeči. Při každé další úpravě souborů na GitHubu (a znovunačtení appky)
zůstanou uložená data zachovaná – mažou se, jen když si v Safari vymažeš data webu nebo appku smažeš.
