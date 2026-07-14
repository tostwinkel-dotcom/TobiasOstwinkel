# SportStudienKompass – Web V1

Lauffähiges Next.js-Projekt mit der ersten umgesetzten Startseite nach dem abgestimmten Designkonzept.

## Enthalten

- responsive Startseite
- langsam bewegtes Hero-Motiv (CSS, mit `prefers-reduced-motion`)
- markanter roter CTA zur kostenlosen Berufsorientierung
- Bereiche „So funktioniert’s“, „Was Du erhältst“, „Berufe entdecken“, Karrierebuch und „Unsere Idee“
- responsive Navigation und Footer
- vorbereitete Routen für Coach, Berufe, Studiengänge, Hochschulen, Karriereauswertung, Idee, FAQ und Rechtstexte
- lokale Bildassets ohne externe Abhängigkeiten

## Start

```bash
npm install
npm run dev
```

Dann `http://localhost:3000` öffnen.

## Produktionsprüfung

```bash
npm run check
npm start
```

## Aktueller Stand

Die Startseite ist funktional. Die Unterseiten sind bewusst als Platzhalter angelegt und werden in den nächsten Schritten mit Datenbank, Import und Coach-Logik verbunden.
