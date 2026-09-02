# malejpodnik

Web pro „malej podnik" – brunch a výběrová káva v Příbrami.

## Status

Rozpracované. Poslední verze přenesená z Claude chatu (`variant-photo.html`
→ přejmenováno na `index.html`), tady se v ní pokračuje.

## Brief

Landing page pro kavárnu/brunch podnik **malej podnik** v Příbrami
(`malejpodnik.cz`). Nabídka: brunch, snídaně, vejce Benedikt, výběrová
káva z pražírny Nordbeans. Otevřeno denně 8–16, brunch podáváme do 15 hodin.

## Stack

Statický web, jeden soubor `index.html` (inline CSS, bez build stepu).
Fotky vložené přímo v souboru jako base64 (`data:image/...;base64,`).

- Fonty: Google Fonts – Fraunces (nadpisy), Instrument Serif (akcenty/kurzíva),
  Work Sans (běžný text)
- Barevná paleta (CSS proměnné v `:root`): cream, espresso, yolk (žloutek),
  plum, sage

## Konvence

Řídí se konvencemi z kořenového [`CLAUDE.md`](../CLAUDE.md) – vlastní
GitHub repo `malejpodnik`, nezávislé na kořenovém repu workspace.
