# Weihnachten – „Hoch die Hände, Jahresende!“

Gemeinsamer A3-Fotokalender (Kalender Buddy) und geheime Wichtel-Auslosung (Wichtelfreund) in einer Seite.

Online: https://weihnachten.inandoutliner.de (noch nicht aktiv)

- `index.html` – die ganze App
- `config.js` – Supabase-Adresse, öffentlicher Schlüssel, Anmeldeschluss
- `fonts/` – Handschrift „Jonathan Hand“

Daten (Kalenderseiten, Fotos, Wichtel-Teilnehmer) liegen in Supabase, nicht im Repo.
Vor dem Start prüfen: E-Mail-Adressen der Teilnehmer dürfen nicht für jeden lesbar sein.

## Fotokalender A4 (`a4/`)

Kopie vom Kalender Buddy für einen A4-Kalender zu zweit: ohne Monatsaufteilung nach Personen, ohne Wichteln.
Fotos kommen von beliebig vielen iPhones (gleicher Familien-Code), alle sehen denselben Stand.

Online: https://weihnachten.inandoutliner.de/a4/

- Druck: WIRmachenDRUCK Wandkalender A4 hoch, Wire-O. PDF mit 13 Seiten (Deckblatt + 12 Monate), 216 × 303 mm inkl. 3 mm Beschnitt (Endformat 210 × 297 mm), 300 dpi.
- Nutzt `config.js` und `fonts/` aus dem Hauptordner und dieselbe Supabase-Tabelle `pages`; die Seiten heißen dort `a4-cover`, `a4-m01` … `a4-m12`, Fotos liegen unter `photos/a4/`.
- Stile sind im A3-Raster entworfen und werden beim Anlegen auf A4 verkleinert (`toA4`).

Inhaltskarte für Änderungen: [KARTE.md](KARTE.md)
