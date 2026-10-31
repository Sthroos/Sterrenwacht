# Sterrenwacht

Een roguelite torenverdediging voor in de browser. Houd de kristalspits staande tegen golven uit de leegte, kies na elke golf een zegen en bouw met ethersplinters blijvende upgrades op in de Hemelboom.

Het hele spel is één bestand: `index.html`. Geen build-stap, geen afhankelijkheden. Het geluid wordt in de browser zelf opgewekt (Web Audio).

## Spelen

Open `index.html` in een browser, of speel de GitHub Pages-versie.

## GitHub Pages aanzetten

1. Ga naar **Settings → Pages**.
2. Kies bij **Source**: *Deploy from a branch*.
3. Kies branch `main` en map `/ (root)`, en klik **Save**.
4. Na een minuut staat het spel op `https://sthroos.github.io/Sterrenwacht/`.

## Opslag

Voortgang (splinters, Hemelboom, rangen, prestaties, collectie) staat in `localStorage` van de browser, per domein. Voortgang uit een andere versie (de claude.ai-pagina of een gedownload bestand) komt dus niet automatisch mee. Wissen kan via **Voortgang wissen** in het hoofdmenu.

## Licentie

AGPL-3.0, zie [LICENSE](LICENSE).
