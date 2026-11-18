# Inhaltskarte

Automatisch erzeugt mit `werkstatt/werkzeuge/karte.py`. Stand: cbd5f58, 2026-11-18: README

Vorgehen: Abschnitt hier finden → `grep -n "<Titel>" index.html` → nur diesen Bereich lesen.

## `index.html` – Hoch die Hände, Jahresende!
846 Zeilen, 82 KB.

**Bedien-Bereiche (HTML)**

- 480: `<section>` ${pid}
- 493: `<section>` wichteln
- 513: `<aside>` side

**Abschnitte im Code** (Suchbegriff = Titel)

| Zeile | Abschnitt | Funktionen |
|---|---|---|
| 213–247 | Hoch die Hände, Jahresende! — Kalender Buddy + Wichtelfreund | ownerOf, useFont, $, esc, uid, clamp, toast |
| 247–289 | Speicher: Supabase oder Demo im Browser | demoBackend, supaBackend |
| 289–313 | Bilder | img, isHeic, decodeFile, prepUpload |
| 313–318 | Kalendarium | daysIn, firstDow |
| 318–431 | Seite zeichnen (Einheit: mm) | photoCanvas, hex, coverDraw, rr, wrapLines, fontOf, textBox, drawPage, drawEl |
| 431–459 | Stile (Presets) | applyPreset, defaultPage |
| 459–470 | Zustand | pageOf, pickMe |
| 470–504 | Startseite | renderMain, scheduleAll, thumbs |
| 504–721 | Editor | openEditor, closeEditor, fitCanvas, handlesOf, handleAt, cursorFor, scaleEl, bandBox, bandHandles, bandDist, edRender, toPage … +17 |
| 721–744 | Export | ensureFonts, waitImages, renderPrint, exportPDF, exportPNG |
| 744–817 | Wichtelfreund: Schloss-Prinzip | pwKey, makeKeys, sealFor, openBox, norm, assign, refreshWichtel, runDraw, modal, wichtelAction |
| 817–846 | Start | gate, start |
