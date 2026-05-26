BoulesDay — website bundel
==========================

Statische HTML, geen build-stap. Plaats alle bestanden in de webroot.

Structuur
---------
  /                        ->  site/index.html        (Nederlandse landing)
  /handleiding.html        ->  site/handleiding.html  (NL handleiding)
  /en/                     ->  site/en/index.html     (English landing)
  /en/handleiding.html     ->  site/en/handleiding.html
  /privacy.html            ->  (nog toe te voegen)

Bestanden in deze bundel
------------------------
  index.html               NL landing
  handleiding.html         NL handleiding
  hero-schema.png          iPad-screenshot in de hero
  screenshot-opzetten.png  screenshot naast de stappen
  sfeer-baan.jpg           PLACEHOLDER — vervangen door echte foto
  en/index.html            EN landing
  en/handleiding.html      EN handleiding
  en/hero-schema.png       (kopie — kan vervangen door EN-screenshot)
  en/screenshot-opzetten.png  (idem)
  en/sfeer-baan.jpg        (idem)

Wat is nieuw in deze versie
---------------------------
- Engelse versie onder /en/, met taalwisselaar NL · EN rechtsboven.
- "Wat het doet" / "What it does" uitgebreid naar 6 stappen, conform de app.
- Nieuwe sectie "Over het schema" / "About the schedule" met
  baan-types, forfait 13-6 en NJBB-bronvermelding.
- Handleiding uitgebreid met "Hoe maakt de app het schema?" en
  "Officiële regels en bronnen".

Nog te doen
-----------
- sfeer-baan.jpg vervangen door echte foto van een jeu-de-boulesbaan
  met iPad op klaptafel. Behoud de bestandsnaam in beide /en/ en root.
- privacy.html toevoegen (de link in de footer verwijst er nu naar).
- Optioneel: aparte EN-screenshots in /en/ als je app in EN draait.

Updaten
-------
Bestanden zijn statische HTML. Tekstwijzigingen kun je rechtstreeks doen
en de bestanden opnieuw uploaden. Geen database, geen CMS.

Aanbevolen deploy-flow: GitHub-repo + Cloudflare Pages.
Zie workflow.md (bij de site-deliverables in Drive) voor details.
