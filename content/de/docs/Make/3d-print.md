---
title: "Selber 3D drucken"
linkTitle: "3D-Druck"
weight: 1
description: >
  Alle Infos um die gedruckten OpenLift Teile selber zu drucken.
---

Gedruckt werden müssen insgesamt 8 Teile, 9 wenn du eine eigene Einlegeplatte baust und den Reduzierring in der Einlegeplatte verwenden möchtest und 10 Teile, wenn du die Alu Einlegeplatte selber gefräst hast. 

Es kann im Prinzip jeder mit einem 3D-Drucker die Teile selber drucken. Dein 3D-Drucker sollte sorgfältig Kalibriert sein und maßhaltig drucken können, damit alle Teile so passen, wie es vorgesehen ist. Bis auf den Reduzierring und dem Hülsenmutterlager werden alle Teile in PETG gedruckt. Die Materialwahl kann geändert werden, es ist aber zu bedenken, dass der Schrumpfwert anderer Materialien von PETG stark abweichen kann. PLA, egal in welcher Form, sollte, bis auf beim Reduzierring, komplett vermieden werden.

Beim Hülsenmutterlager empfiehlt es sich ein Filament zu nutzen, dass gute Gleiteigenschaften hat. Das Lager sollte mit 0.4er Nozzle gedruckt werden.

## STL-Dateien

Die Links zu den aktuellen STL-Dateien findest du in der [Teileliste](/docs/bom/) oder im [GitHub Projekt](https://github.com/nachdenksport/openlift).

## Druckeinstellungen

* Filament: PETG, z.B. Prusament PETG
* Perimeter: 5
* Num. Top/Bottom Layers: 5
* Infill: 25%
* Infill pattern: Gyroid, Grid, Rectilinear
* Support: No
* Brim: No
* Detect thin walls: No

Einstellungen wie Layer Höhe, oder Extrusion Width sind stark davon abhängig welche Nozzle Größe verwendet wird und welches Teil gedruckt wird. Wer öfter 3D druckt sollte diese Einstellungen selber wählen können.