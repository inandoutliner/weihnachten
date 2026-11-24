# Inhaltskarte

Automatisch erzeugt mit `werkstatt/werkzeuge/karte.py`. Stand: 23cda69, 2026-11-23: Weihnachten: App-Icon (Faltstern) fürs iPhone

Vorgehen: Abschnitt hier finden → `grep -n "<Titel>" index.html` → nur diesen Bereich lesen.

## `index.html` – Hoch die Hände, Jahresende!
849 Zeilen, 82 KB.

**Bedien-Bereiche (HTML)**

- 483: `<section>` ${pid}
- 496: `<section>` wichteln
- 516: `<aside>` side

**Abschnitte im Code** (Suchbegriff = Titel)

| Zeile | Abschnitt | Funktionen |
|---|---|---|
| 216–250 | Hoch die Hände, Jahresende! — Kalender Buddy + Wichtelfreund | ownerOf, useFont, $, esc, uid, clamp, toast |
| 250–292 | Speicher: Supabase oder Demo im Browser | demoBackend, supaBackend |
| 292–316 | Bilder | img, isHeic, decodeFile, prepUpload |
| 316–321 | Kalendarium | daysIn, firstDow |
| 321–434 | Seite zeichnen (Einheit: mm) | photoCanvas, hex, coverDraw, rr, wrapLines, fontOf, textBox, drawPage, drawEl |
| 434–462 | Stile (Presets) | applyPreset, defaultPage |
| 462–473 | Zustand | pageOf, pickMe |
| 473–507 | Startseite | renderMain, scheduleAll, thumbs |
| 507–724 | Editor | openEditor, closeEditor, fitCanvas, handlesOf, handleAt, cursorFor, scaleEl, bandBox, bandHandles, bandDist, edRender, toPage … +17 |
| 724–747 | Export | ensureFonts, waitImages, renderPrint, exportPDF, exportPNG |
| 747–820 | Wichtelfreund: Schloss-Prinzip | pwKey, makeKeys, sealFor, openBox, norm, assign, refreshWichtel, runDraw, modal, wichtelAction |
| 820–849 | Start | gate, start |

## `a4/index.html` – Fotokalender A4
753 Zeilen, 71 KB.

**Bedien-Bereiche (HTML)**

- 461: `<section>` ${pid}
- 491: `<aside>` side

**Abschnitte im Code** (Suchbegriff = Titel)

| Zeile | Abschnitt | Funktionen |
|---|---|---|
| 209–242 | Fotokalender A4 — Kopie vom Kalender Buddy, für zwei iPhones | useFont, $, esc, uid, clamp, toast |
| 242–270 | Speicher: Supabase oder Demo im Browser | demoBackend, supaBackend |
| 270–294 | Bilder | img, isHeic, decodeFile, prepUpload |
| 294–299 | Kalendarium | daysIn, firstDow |
| 299–412 | Seite zeichnen (Einheit: mm) | photoCanvas, hex, coverDraw, rr, wrapLines, fontOf, textBox, drawPage, drawEl |
| 412–446 | Stile (Presets) | toA4, applyPreset, defaultPage |
| 446–451 | Zustand | pageOf |
| 451–483 | Startseite | renderMain, scheduleAll, thumbs |
| 483–698 | Editor | openEditor, closeEditor, fitCanvas, handlesOf, handleAt, cursorFor, scaleEl, bandBox, bandHandles, bandDist, edRender, toPage … +17 |
| 698–721 | Export | ensureFonts, waitImages, renderPrint, exportPDF, exportPNG |
| 721–724 | Dialog | modal |
| 724–753 | Start | gate, start |
