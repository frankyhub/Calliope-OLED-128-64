
> Diese Seite bei [https://frankyhub.github.io/calliope-oled-128-64/](https://frankyhub.github.io/calliope-oled-128-64/) öffnen

## Als Erweiterung verwenden

Dieses Repository kann als **Erweiterung** in MakeCode hinzugefügt werden.

* öffne [https://makecode.calliope.cc/](https://makecode.calliope.cc/)
* klicke auf **Neues Projekt**
* klicke auf **Erweiterungen** unter dem Zahnrad-Menü
* nach **https://github.com/frankyhub/calliope-oled-128-64** suchen und importieren

## Dieses Projekt bearbeiten ![Build Status Abzeichen](https://github.com/frankyhub/calliope-oled-128-64/workflows/MakeCode/badge.svg)

Um dieses Repository in MakeCode zu bearbeiten.

* öffne [https://makecode.calliope.cc/](https://makecode.calliope.cc/)
* klicke auf **Importieren** und dann auf **Importiere URL**
* füge **https://github.com/frankyhub/calliope-oled-128-64** ein und klicke auf Importieren

## Blockvorschau

Dieses Bild zeigt den Blockcode vom letzten Commit im Master an.
Die Aktualisierung dieses Bildes kann einige Minuten dauern.

![Eine gerenderte Ansicht der Blöcke](https://github.com/frankyhub/calliope-oled-128-64/blob/master/calliope-oled.png)


## Befehle
- init(addr: number)
initialize OLED module. addr: OLED I2C address, it maybe 60 or 61, depend on hardware, default is 60.

- zoom(d: boolean = true)
set zoom mode. In zoom mode, it will show in double size.
d: mode
true, zoom mode.
false, normal mode.

- on()
turn on OLED.

- off()
turn off OLED.

- clear()
clear all content in OLED.

- draw()
force redraw the content.

- invert(d: boolean = true)
show in invert mode.

- pixel(x: number, y: number, color: number = 1)
set a pixel in OLED.

x, X alis position, 0 - 63 in zoom mode, 0 - 127 in normal mode.
y, Y alis position, 0 - 31 in zoom mode, 0 - 63 in normal mode.
color, draw color, it can be 1 or 0.

- showString(x: number, y: number, s: string, color: number = 1)
show a text at specified position.

x, X alis position, 0 - 11 in zoom mode, 0 - 23 in normal mode.
y, Y alis position, 0 - 3 in zoom mode, 0 - 7 in normal mode.
s, the text will be show
color, draw color, it can be 1 or 0.

- showNumber(x: number, y: number, num: number, color: number = 1)
show a number at specified position.

x, X alis position, 0 - 11 in zoom mode, 0 - 23 in normal mode.
y, Y alis position, 0 - 3 in zoom mode, 0 - 7 in normal mode.
num, the number will be show
color, draw color, it can be 1 or 0.

- hline(x: number, y: number, len: number, color: number = 1)
draw a horizontal line.

(x, y), start point
len, length of the line
color, draw color, it can be 1 or 0.

- vline(x: number, y: number, len: number, color: number = 1)
draw a vertical line.

(x, y), start point
len, length of the line
color, draw color, it can be 1 or 0.

- rect(x1: number, y1: number, x2: number, y2: number, color: number = 1)
draw a rectangle.

(x1, y1), start point
(x2, y2), end point
color, draw color, it can be 1 or 0.

#### Metadaten (verwendet für Suche, Rendering)

* for PXT/calliopemini
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
