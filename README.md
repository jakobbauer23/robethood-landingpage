# Landingpage — Vorschau

Arbeitsstand der Landingpage zur Abstimmung. Kein Livebetrieb.

## Ansehen

Oben auf dieser Seite auf **Code → Download ZIP**, das Archiv entpacken und
`index.html` doppelklicken. Mehr ist nicht nötig: Alle Pfade sind relativ, es
gibt keinen Build und keinen Server. Die Seite läuft vollständig offline,
Videos eingeschlossen.

Wer mit git arbeitet, kann stattdessen klonen und `index.html` öffnen.

## Was drin ist

| Datei | Inhalt |
|---|---|
| `index.html` | Die Landingpage. CSS und JS stehen inline, keine Webfonts, keine Fremdskripte außer der Statistik. |
| `impressum.html`, `datenschutz.html` | Rechtsseiten. |
| `assets/` | Bildmarke, Screenshots, die beiden Videos und deren Standbilder. |

## Zwei Hinweise fürs Ansehen

**Die Videos starten erst auf Antippen.** Das ist Absicht, kein Fehler: Auf der
Seite bewegt sich nichts von allein. Bis zum Antippen wird nur das Standbild
geladen, die Videodatei selbst nicht — deshalb baut die Seite trotz rund 30 MB
Videomaterial in unter 300 KB auf.

**Bitte auch am Handy ansehen.** Nahezu der gesamte Traffic kommt aus mobilen
In-App-Browsern; die Seite ist dafür gebaut. Am Desktop steht das Hero-Video
rechts neben der Überschrift, am Handy rückt es über den Button. Am Rechner
lässt sich das mit den Entwicklerwerkzeugen des Browsers nachstellen
(F12, dann die Geräteansicht).

## Noch offen

- `data-domain` für die Statistik steht auf dem Platzhalter `[[DOMAIN]]`.
- Der Link zur Schritt-für-Schritt-Anleitung ist noch nicht gesetzt (`data-todo="anleitung"`).
- Die Zahlen in den Videos (Trustpilot 4,6 / 1201 Bewertungen, 14.000 Teilnehmer)
  weichen von den Zahlen auf der Seite ab (4,8 / über 2.300, über 20.000).
