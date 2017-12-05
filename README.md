# Arkanoid
Ein Uni Projekt mit dem Ziel das bekannte Retro Spiel "Arkanoid" mit JavaScript nachzuprogrammieren.

## Entwickler

- Simon Tebbe
- Oliver Rehbach
- Janic Steckelbach

## Datum der Fertigstellung

05.12.2017

## How to play

- ***D*** oder ***rechte Pfeiltaste***: Bewegt das Pannel nach rechts
- ***A*** oder ***linke Pfeiltaste***: Bewegt das Pannel nach links
- Steuerung des Pannels ist auch mit der ***Maus*** möglich. (Pannel = X-Position der Maus)
- ***P***: Spiel pausieren
- ***Leertaste***: Spiel beginnen -> Ball vom Pannel lösen / Weiterspielen, nachdem der Ball nicht mit dem Paddel getroffen wurde
- ***B***: Bot starten (Für Testzwecke gedacht)
- ***1 - 4***: Mit der jeweiligen Taste das entsprechende Level starten
- ***M***: Schaltet den sound an/aus


## Wer war für was zuständig?

### Simon Tebbe:
- Collision Detection (Collision des Balls mit: den Blöcken, dem Pannel und den Wänden. Jeweils natürlich mit Beachtung des korrekten Abprallens in die richtige Richtung)
- Power Ups (Ballgeschwindigkeit erhöhen/verringern, Paddle vergrößern/verkleinern, Leben hinzufügen)
- Blöcke und deren Management
- Leveldesign
- Scoreboard (Logik)
- Tastenhandler
- Refactoring
- Transparenz der Blöcke

### Oliver Rehbach:
- Menü
- Farbänderung des Balls
- Levelauswahl
- Design
- Scoreboard (Design)
- Tastenhandler
- Refactoring

### Janic Steckelbach:
- Musik und Soundeffekte
- Farbänderung der Blöcke je nach Leben der Blöcke
- Steuerung mit der Maus
- Pausieren des Spiels
- Aus-/Einschalten der Musik und Soundeffekten
- Bot zum testen
- Tastenhandler (keypaddle)


## Known Bugs:
- Läuf je nach Leistung des PCs langsamer als vorgesehen
- Collision Detection in einigen wenigen Fällen noch etwas ungenau
- Internet Explorer wird nicht unterstützt


## License
MIT License

Copyright (c) 2017 Simon Tebbe, Oliver Rehbach, Janic Steckelbach

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Lizensen zu verwendeten Soundeffekten, Lieder und Bildern

### Soundeffekte, Lieder und Bilder stehen unter der "creative commons" Lizens (https://creativecommons.org/licenses/by-nc/3.0/legalcode)

#### Links zu den einzelnen Soundeffekten und Liedern:
- Hintergrundmusik: https://freesound.org/people/FoolBoyMedia/sounds/320232/
- Sound Ball down (Sad Trombone): https://freesound.org/people/Benboncan/sounds/73581/
- Sound Game Over: https://freesound.org/people/noirenex/sounds/159408/
- Voice Game Over: https://freesound.org/people/Rocotilos/sounds/178876/
- Sound Block Gruen: https://freesound.org/people/jorickhoofd/sounds/160043/
- Sound Block Blau: https://freesound.org/people/Benboncan/sounds/103629/
- Sound Block Rot: https://freesound.org/people/acclivity/sounds/19987/
- Sound Win: https://freesound.org/people/Tuudurt/sounds/275104/

#### Links zum Hintergrundbild:
- Hintergrundbild Level 1: https://pixabay.com/de/science-fiction-abenteuer-raumschiff-2907434/
- Hintergrundbild Level 2: https://pixabay.com/de/landschaft-wasser-felsen-raumschiff-1328858/
- Hintergrundbild Level 3: https://pixabay.com/de/raumsonde-pioneer-10-gasnebel-2412430/