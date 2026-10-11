# Ausrüstung

Gegenstände werden je nach Typ mit der entsprechenden Generatormatrix erstellt. Es muss aus jeder Spalte genau ein Eintrag gewählt werden, und insgesamt entsprechend der zur Verfügung stehenden P ausgewählt werden.

::: {.accordion data-title="Beispiele"}
- Eine Einfache Rüstung gibt 2x B und 2x C:
	- Stichfeste Weste: Gewöhnlich (B), Fernkampf-Rüstung: 0 (C), Nahkampf-Rüstung: 2 (B), Körperteile: Torso (C)
	- Leichte Rüstung: Auffällig (C), Fernkampf-Rüstung: 1 (B), Nahkampf-Rüstung: 1 (C), Körperteile: Torso + Kopf (B)
- Eine Normale Schusswaffe gibt 1x A, 2x B und 2x C:
	- SMG: Reichweite: Normal (B), Gewöhnlich (B), Schaden: 1 (C), Krit-Schaden: 0.5 (C), Tick: 2|4 (A)
	- Shotgun: Reichweite: Gering (C), Auffällig (C), Schaden: 2 (B), Krit-Schaden: 2 (A), Tick: 4|8 (B)
:::

## Auffälligkeit

Viele Gegenstände besitzen einen Auffälligkeitswert. Dieser beschreibt, welches Aufsehen die Waffe bei anderen Personen erregen, die den Umgang mit Waffen gewohnt sind, z.B., Gang-Mitglieder, andere Söldner oder Sicherheitskräften.

Auffälligkeit           | Beispiel         | Beschreibung 
------------------------|------------------|---------------------------------------------------------------------
Integriert / Getarnt    | Gehstock-Pistole | Der Gegenstand ist in etwas anderem verborgen, z.B. in einem unauffälligem Gegenstand oder in einem Cyborg-Teil. Ein Integrierter Gegenstand wird auch bei einem Sicherheitscheck nicht gefunden (wohl aber der "behausende" Gegenstand)
Versteckt / Unauffällig | CCW Pistole      | Der Gegenstand ist generell nicht zu sehen, und kann meist nur bei einem Sicherheitscheck gefunden werden
Gewöhnlich              | Gewehr           | Der Gegenstand ist generell offen sichtbar, sieht für Personen die an Waffen gewöhnt sind jedoch nicht bedrohlich aus. Ein Gewöhnlicher Gegenstand kann nur gegenüber Zivilisten verborgen werden und wird ansonsten auch ohne Sicherheitscheck bemerkt.
Auffällig               | Minigun          | Der Gegenstand ist für jeden zu sehen und kann nicht von einer Person verborgen getragen werden und gleichzeitig zugreifbar sein (aber z.B. in einem großen verschlossenen Behälter). Der Gegenstand sieht illegal aus und wird entsprechend kontrolliert, und löst generell Unmut aus.

## Rüstung

P | Auffälligkeit | Fernkampf-Rüstung | Nahkampf-Rüstung | Körperteile
--|---------------|-------------------|------------------|--------------
A | Versteckt     | 2                 | 3                | Alle
B | Gewöhnlich    | 1                 | 2                | Torso + Kopf
C | Auffällig     | 0                 | 1                | Torso

- Körperteile: Bestimmt, welche Körperteile durch die Rüstung geschützt werden. Der Nah-/Fernkampf-Rüstungswert wird nur für diese Körperteile erhöht.
- Fernkampf-Rüstung: Erhöht den Fernkampf-Rüstungswert, der von Fernkampfangriffen abgezogen wird
- Nahkampf-Rüstung: Erhöht den Nahkampf-Rüstungswert, der von Nahkampfangriffen abgezogen wird

 Typ    | P
--------|----------------
Einfach | 2x B, 2x C
Normal  | 1x A, 2x B, 1x C
Gut     | 2x A, 2x B

### Exoskelett

Exoskelette können anstelle einer Rüstung getragen werden.

P | Fernkampf-Rüstung | Nahkampf-Rüstung | Kapazität | Athletik-Bonus
--|-------------------|------------------|-----------|-------------—
S | Immun             | Immun            | 30        | 10
A | 3                 | 4                | 12        | 4
B | 2                 | 3                | 8         | 2
C | 1                 | 2                | 4         | 1

- Auffälligkeit: Ein Exoskelett ist immer Auffällig
- Fernkampf-Rüstung: Erhöht den Fernkampf-Rüstungswert, der von Fernkampfangriffen abgezogen wird
- Nahkampf-Rüstung: Erhöht den Nahkampf-Rüstungswert, der von Nahkampfangriffen abgezogen wird
- Kapazität: Für Erweiterungen die in das Exoskelett eingebaut sind.
- Atheltik-Bonus: Gibt Vorteil auf Athletik-Würfe bei denen das Exoskelett helfen kann.

## Schusswaffen

P | Reichweite | Auffälligkeit   | Schaden | Krit-Schaden | Tick
--|------------|-----------------|---------|--------------|------
S | Unendlich  | Integriert      | 8       | 4            | 1\|2
A | Hoch       | Versteckt       | 4       | 2            | 2\|4
B | Normal     | Gewöhnlich      | 2       | 1            | 4\|8
C | Gering     | Auffällig       | 1       | 0.5          | 8\|12

- Reichweite: Reichweite im Kampf
	- Gering: Selbe Zone, danach Nachteil von 2 pro weitere Zone. Nahkampfdeckung nur wenn bereits im Nahkampf verwickelt
	- Normal: Selbe oder benachbarte Zone, danach Nachteil von 2 pro weitere Zone. Nahkampfdeckung innerhalb der selben Zone
	- Hoch: Bis zu 3 Zonen entfernt (selbe Zone + 3 weitere), danach Nachteil von 1 pro weitere Zone. Nahkampfdeckung in der selben Zone
	- Unendlich: hinreichend unendlich, kein Angriffs-Nachteil durch Entfernung. Kann von einem Punkt außerhalb der Karte schießen. Nahkampfdeckung in der selben oder benachbarten Zone
- Schmerz: Schaden, die beim Ziel verursacht werden
- Krit-Schaden: Bonus-Schaden pro Bonus Erfolg. Bei 0.5 wird aufgerundet.
- Tick: Anzahl an Ticks (Schnell | Langsam), die das Feuern der Waffe bis zum nächsten Schuss dauert, bzw. wie lange das Nachladen dauert.

<!--

    - Gering: bis zu 6/4 Felder entfernt (Kardinal/Diagonal), darüber hinaus gibt es einen Angriffs-Nachteil von 1 pro 1 weiteres Feld, Nahkampf-Deckung bei Entfernung <= 2
    - Normal: bis zu 12/8 Felder entfernt (Kardinal/Diagonal), darüber hinaus gibt es einen Angriffs-Nachteil von 1 pro 2 weitere Felder, Nahkampf-Deckung bei Entfernung <= 3
    - Hoch:  bis zu 18/12 Felder entfernt (Kardinal/Diagonal), darüber hinaus gibt es einen Angriffs-Nachteil von 1 pro 3 weitere Felder, Nahkampf-Deckung bei Entfernung <= 5
    - Unendlich: hinreichend unendlich, keine Angriffs-Nachteil durch Entfernung. Kann von einem Punkt außerhalb der Karte schießen. Nahkampf-Deckung bei Entfernung <= 6

-->

 Type   | P
--------|----------------
Einfach | 2x B, 3x C
Normal  | 1x A, 2x B, 2x C
Gut     | 2x A, 2x B, 1x C
Spezial | 1x S, 2x B, 2x C

### Spezialmunition

Spezialmunition sorgt kann in bestimmten Situationen für bessern Effekt. Es kann nur ein
Munitionstyp gleichzeitig aktiviert sein. Ein Wechsel des Munitionstyps dauert eine Nachladeaktion. Munition wird nicht verbraucht, muss aber für jede Waffe
separat gekauft werden.

Munitionstyp   | Effekt
---------------|--------------------------------------------------------------------
Ausbalanciert  | Erhöht die Basis-Reichweite um 1 Zone.
Wundreißer     | +1 Schaden, Rüstung wird, sofern vorhanden, als 1 höher behandelt
Panzerbrechend | Rüstung wird, sofern vorhanden, als um 1 verringert behandelt
Schock         | +1 Schaden gegen Cyborgs / Drohnen
Leuchtspur     | +1 Vorteil (kumulativ) pro konsekutiven Schuss auf das gleiche Ziel (Start +0)
Kryo           | Addiert 1 Tick auf Tickzeit des Ziels

## Nahkampfwaffen

P | Auffälligkeit   | Schmerz | Krit-Schaden | Tick
--|-----------------|---------|--------------|------------
S | Integriert      | 8       | 5            | 1\|2
A | Versteckt       | 4       | 3            | 2\|4
B | Gewöhnlich      | 2       | 2            | 4\|8
C | Auffällig       | 1       | 1            | 8\|12

- Für Angriffe muss sich generell der Angreifer an das Ziel heran positionieren.
- Tick ist Wert, der auf die Tickzeit der Aktionen addiert wird.
- Tick: Anzahl an Ticks (Schnell | Langsam), die ein Angriff mit der Waffe dauert.

Rest siehe [Schusswaffen](#schusswaffen-1).

 Typ    | P
--------|----------------
Einfach | 2x B, 2x C
Normal  | 1x A, 2x B, 1x C
Gut     | 2x A, 2x B
Spezial | 1x S, 2x B, 1x C

## PSI-Verstärker

Ein PSI-Verstärker verstärkt PSI-Aktionen

P | Reichweite    | Tick | Heimlichkeit | Fühlen-Erfolge | Manip.-Erfolge
--|---------------|------|--------------|----------------|--------------
S | Hoch          | 1    | 5            | +2             | +2
A | Normal        | 2    | 3            | +1             | +1
B | Gering        | 3    | 2            | 0              | 0
C | Berührung     | 4    | 1            | -1             | -1

- Reichweite
	- Berührung: Wie Nahkampfwaffe, oder mit Nachteil von 2 innerhalb der selben Zone
	- Gering: Selbe Zone, danach Nachteil von 2 pro weitere Zone
	- Normal: Selbe oder benachbarte Zone, danach Nachteil von 1 pro weitere Zone
	- Hoch: Bis zu 3 Zonen entfernt (selbe Zone + 3 weitere), danach Nachteil von 1 pro weitere Zone
- Tick: Tickzeit für PSI-Aktionen im Kampf
- Heimlichkeit: Schwierigkeit für das Ziel, die PSI-Aktion zu Bemerken
- Fühlen/Manipulation-Erfolge: Senkt/Erhöht die Anzahl der erzielten Erfolge einer PSI-Aktion.

<!--

S| 24/18         | 1        | 5            | +2             | +2
A| 12/8          | 2        | 3            | +1             | +1
B| 8/6           | 3        | 2            | 0              | 0
C| 4/3           | 4        | 1            | -1             | -1

- Reichweite: Entfernung ohne Nachteil, danach für jedes Vielfache der Reichweite -1

-->

 Typ    | P
--------|----------------
_Ohne_    | 5x C
Einfach | 2x B, 3x C
Normal  | 1x A, 2x B, 2x C
Gut     | 2x A, 2x B, 1x C
Spezial | 1x S, 2x B, 2x C

## Verbrauchsgegenstände

Verbrauchsgegenstände werden einmalig gekauft, und stehen dann während einer Mission in entsprechender Anzahl zur Verfügung. Zwischen Missionen können die Verbrauchsgegenstände kostenlos wieder aufgefüllt werden.

### Granaten & Minen

Eine Granate können wahlweise als Minen erstellt werden, welche den Effekt der Granate über den Zünder einer Mine auslöst.

P | Effektstärke | Radius
--|--------------|--------
A | 3            | d5+3
B | 2            | d3+1
C | 1            | d2

- Effekt:
    - Rauch: Gibt Deckung und versteckt alle Charaktere im Rauch vor Sicht (inkl. Nacht- u. Wärmesicht). Effekt gilt in beide Richtungen (in Rauch rein/heraus)
    - Fragment: Explosion
    - Spezial: Flash, AP, EMP
- Effektstärke (N):
    - Rauch*: Erhöhte Deckung & Schwierigkeit für Wahrnehmung (der Rauch selbst ist offensichtlich)
    - Fragment: x3 Schaden, Rüstung wird um 1 höher betrachtet
    - Spezial:
        - Flash: x8 Ticks, die Charaktere ausgeknockt werden
		- EMP: x3 Schaden gegen Cyborgs/Drohnen, sonst 0 Schaden
        - AP: x2 Schaden, Rüstung wird um 1 niedriger betrachtet
- Radius: Es können nur Charaktere innerhalb einer Zone oder in der Nähe eines Interaktionspunktes getroffen werden. Anzahl der Charaktere die vom Effekt maximal betroffen sein können. Bei Rauchgranaten beschränkt dies die Größe der entstehenden Rauch-Zone, bei anderen Effekten ist es die maximale Anzahl betroffener Charaktere. Welche Charaktere genau getroffenen werden, wird vom Spielleiter final entschieden.

 Typ    | P
--------|------------
Einfach | 1x B, 1x C
Normal  | 2x B
Gut     | 1x A, 1x B

### Stims

Im Kampf einsetzbare Medizin/Aufputschmittel. Können auch als Tabletten, Pillen oder in anderen Formen auftreten.

P | Effektstärke | Aktivierungsdauer
--|--------------|-------------------
A | 6            | 2
B | 4            | 4
C | 2            | 8

- Effekt
    - Stressreduktion: Reduziert Stress (nicht unter Basisstress)
    - Schmerzreduktion: Reduziert Gesamtschmerz, aber keinen Körperteilschmerz
	- Fokus-Boost: Stellt Effektstärke Fokus sofort her, auch über das Maximum heraus
	- Stamina-Boost: Stellt Effektstärke Stamina sofort her, auch über das Maximum heraus
- Effektstärke: Menge an Stress/Gesamtschmerz/Fokus/Stamina die reduziert/wiederhergestellt wird
- Aktivierungsdauer: Ticks die zum Einsetzen benötigt werden.

 Typ    | P
--------|------------
Einfach | 1x B, 1x C
Normal  | 2x B
Gut     | 1x A, 1x B

### Wanzen

Sehr kleine, unauffällige Sensoren die an verschiedenen Oberflächen angebracht werden können.

P | Anzahl Sensoren | Unauffälligkeit | Senderadius
--|-----------------|-----------------|--------------------
A | 3               | 5               | Stadtweit
B | 2               | 3               | Distriktweit
C | 1               | 2               | ca. 2 Häuserblöcke weit

- Anzahl Sensoren: bestimmt wie viele Sensoren bzw. Verbesserungen eingebaut sind
    - Mikrophon
    - Kamera
        - Nachtsicht (zählt als extra Sensor zusätzlich zu Kamera)
        - Wärmebild (zählt als extra Sensor zusätzlich zu Kamera)
    - GPS
    - Anderes
- Unauffälligkeit: Schwierigkeit für eine Wahrnehmungsprobe, um die Wanze zu entdecken
- Senderadius: Bereich in dem auf die Sensoren der Wanze zugegriffen werden kann.

 Typ    | P
--------|----------------
Einfach | 2x B, 1x C
Normal  | 1x A, 1x B, 1x C
Gut     | 2x A, 1x B

## Drohnen

P | Auffälligkeit | Bewegung   | Kapazität | Stabilität | ???
--|---------------|------------|-----------|------------|-----------
S | Getarnt       | Schwarm    | 12        | 24         | 
A | Unauffällig   | Fliegend   | 8         | 12         | 
B | Gewöhnlich    | Kletternd  | 4         | 9          | 
C | Auffällig     | Boden      | 2         | 6          | 

- Bewegung:
    - Boden: Erlaubt bodengebundene, horizontale Bewegung, sowie. Treppen o.ä.
    - Kletternd: Erlaubt Bewegung entlang beliebiger Oberflächen.
    - Fliegend: Erlaubt Bewegung durch die Luft.
	- Schwarm: Statt einer einzelnen Drone handelt es sich um einen kleinen Schwarm fliegender Dronen. Der Schwarm kann sich aufteilen, aber Stabilität und Fähigkeiten werden ebenfalls aufgeteilt.
- Systeme: Anzahl einbaubarer Systeme:
    - Waffensystem: Drone kann mit einer Waffe ausgestattet werden und besitzt die dafür notwendige Fähigkeit auf Stufe 2. Zusätzliche Waffensysteme können diesen Wert um 2 erhöhen.
    - Sensorsystem: Drone besitzt spezielle Wahrnehmung, die auch übertragen werden kann. Die Wahrnehmung entspricht entweder der des Betrachters, oder 2*(Anzahl Sensorsysteme)
    - Panzerung: Erhöht Rüstung um 1, bis zu einem Maximum von 3
    - Kapazität: Erhöht Erweiterungs-Kapazität der Drone um 1
    - Werkzeug: Besitzt Werkzeug und die dafür notwendige Fähigkeit auf Stufe 2. Zusätzliche Werkzeugsysteme können diesen Wert um 2 erhöhen.
    - Anderes
- Stabilität: Trefferpunkte der Drone. Dronen haben nur eine einzige Trefferzone und keinen Gesamtschmerz.
    - Erleidet die Drone Schaden größergleich dem Stabilitätswert und kleiner als der doppelte Stabilitätswert, so zählt sie als beschädigt und ist aktionsunfähig
    - Erleidet die Drone Schaden größergleich dem doppelten Stabilitätswert. so ist sie irreperabel zerstört.
- ???

 Type   | P
--------|----------------
Einfach | 2x B, 3x C
Normal  | 1x A, 2x B, 2x C
Gut     | 2x A, 2x B, 1x C
Spezial | 1x S, 2x B, 2x C

## Cyberware

### Energiequelle

Typ     | Energiequelle       | Kapazität | Beschreibung
--------|---------------------|-----------|---------------------------------------------------------------
Einfach | Batterie            | 12        | Muss nach maximal 20h wieder aufgeladen werden, was bis zu 6h dauert.
Normal  | Bioreaktor          | 25        | Erzeugt Energie durch mehr Essen. Etwa 5x soviel, wie eine normale Person isst. Es gibt spezielle "Energieriegel", die besonders viele Nährstoffe für Bioreaktoren beinhalten
Gut     | Radionuklidbatterie | 40        | Erzeugt Energie ohne weitere Vorraussetzungen. Die Batterie muss alle paar Jahre ausgetauscht werden.
Spezial | Superkondensator    | 20 \| 99   | Erzeugt begrenzte Energie im Normalbetrieb, aber kann bei Bedarf für ca. 10 Minuten nahezu unbegrenzt Energie produzieren. Danach muss der Superkondensator wieder aufgeladen, was bis zu 1h dauert. Dies erlaubt selektive Aktivierung[¹](#cyber-energy-1) von zusätzlicher Cyberware

::: {#cyber-energy-1}
_¹ Basisstress besteht auch für deaktivierte Cyberware._
:::

### Cyborg-Körperteil

P | Auffälligkeit | Rüstung | Kapazität | Basisstress
--|---------------|---------|-----------|-------------
A | Versteckt     | 1       | +1        | 0
B | Gewöhnlich    | 0       | -1        | 1
C | Auffällig     | -1      | -2        | 2

- Auffälligkeit: Gilt für alle in den Körperteil eingebauten Erweiterungen
- Rüstung: Eingebaute Rüstung für Nah-/Fernkampf. Negative Rüstung erhöht den eingehenden Schaden
- Kapazität: Kapazität für das Körperteil (negative Kapazität senkt die Gesamtkapazität)
- Basisstress: Erhöht den Basisstress

 Typ    | P
--------|----------------
Einfach |      2x B, 2x C
Normal  |1x A, 1x B, 2x C
Gut     |2x A, 1x B, 1x C

### Erweiterungen

Erweiterungstyp | Anwendbarkeit
----------------|-----------------------------------------
Beliebig        | Kann (nahezu) überall eingebaut werden.
Sicht           | Cyborg-Kopf, Implantat(Auge), Rüstung(Kopf), Schusswaffen, DiMES, Exoskelett, Drone
Werkzeug        | Cyborg-Arme, DiMES, Exoskelett, Drone
Körper          | Cyborg-Komplettkörper, Rüstung, Exoskelett, Drone
Atmung          | Cyborg-Torso, Rüstung(Kopf), Exoskelett
Spezifisch      | Hängt von genauer Verwendung ab, z.B. ein Fähigkeitsbooster für Schusswaffen kann in einer Schusswaffe eingebaut sein, ein Fähigkeitsbooster für Heimlichkeit aber nicht.
Arme            | Cyborg-Arme, Exoskelett, Drone


Erweiterung                     | Kapazität | Typ               | Beschreibung
--------------------------------|-----------|-------------------|-----------------------------------------------------------------------
Kommunikator                    | 1         | Beliebig          | Erlaubt Kommunikation mit anderen Kommunikatoren
Restlichtverstärker             | 1         | Sicht             | Erlaubt Sicht in Dunkelheit, passiv
Hacking-Werkzeug                | 1         | Werkzeug          | Ermöglicht Software-Hacking
Aktive Camouflage               | 6         | Körper            | Macht den Körper transparent
Gasfilter                       | 2         | Atmung            | Filtert (giftige) Gase aus der Atemluft
Optische Vergrößerung           | 1         | Sicht             | Erlaubt an entfernte oder kleine Dinge heranzuzoomen
Stauraum                        | 0         | Beliebig          | Ermöglicht kleine Gegenstände getarnt zu verstauen
Jammer                          | 2         | Beliebig          | Blockiert Kommunikation
Eingebaute Waffe                | 2\>4\>6     | Beliebig          | Erlaubt eine einfache\|normale\>gute/spezielle Waffe zu verbauen
Geigerzähler                    | 1         | Beliebig          | Meldet Radioaktivität
Sauerstoff-Tanks                | 4         | Atmung            | Bietet Sauerstoff für ca. 10 Minuten
Kamera                          | 1         | Sicht             | Erlaubt Fotos und Videos der aktuellen Sicht zu machen
Audio-Rekorder                  | 1         | Beliebig          | Erlaubt aktuelle Geräusche aufzunehmen
Scheinwerfer                    | 1         | Beliebig          | Macht helles Licht
Automatische Spritze            | 3         | Atmung            | Ermöglicht Spritzen zu laden, die bei Bedarf automatisch injiziert werden
Fähigkeitsbooster               | 2         | Spezifisch        | Gibt einen +1 Vorteil auf einen bestimmten Fähigkeitswert der den Booster involviert. Die genaue Art des Boosters sowie die dadurch verbesserte Fähigkeit müssen bei Erwerb festgelegt werden. Beispiel: Fähigkeitsbooster für Schusswaffen könnte ein Ziellaser sein.
Richtmikrophon                  | 1         | Sicht             | Ermöglicht Hören in Sichtlinie
Infrarotsicht                   | 1         | Sicht             | Ermöglicht Sehen im Infrarotbereich
Nachtsicht                      | 1         | Sicht             | Erlaubt Sicht in Dunkelheit, aktiv
GPS                             | 1         | Beliebig          | Erlaubt die genaue Position festzustellen
Holographische Maske            | 4         | Cyborg-Kopf,DiMES | Erlaubt freies Anpassen von Gesicht
Datenbank                       | 1         | Beliebig          | 
Bionische Stimmbänder           | 2         | Cyborg-Kopf       | 
Kraftbooster                    | 4         | Arme              | Athletik +1, Erlaubt es sehr schwere Dinge zu heben.

Mega-Bohrer
Kletterhände
Seilwinde
Geräuschabsorber
Sprung-Beine
Zähigkeitsbooster
LIDAR-Scanner
Automatische Blende (protection for flashbangs)
Auto-Ausweicher (Fernkampf-Deckung)
Subvocal-Kommunikator (Kommunikator ohne laut zu reden)
Blackbox-Recorder
Eingebaute KI
Holographische Projektion
Typhoon (Eingebaute Granate, die um Nutzer herum auslöst)
Bionische Finger(-abdrücke)
Offensiv-Injektor (Spritzt Gifte/Substanzen in andere)
Magnete
Automatische Reparatur
Schockabsorber (Kein Fallschaden)
Neodymium-Schild
Temperatur-Isolierung
Schmerzfilter
Sprinter-Beine
Gleitmembran
Schwimmflossen-Kit
3D-Drucker
Schweißbrenner
Dokumentenscanner
Druckregulator (high/low pressure, e.g. on outside of plane or deep on the ocean floor)
Gedächtnis-Backup
Stimmanalysator (Lügendetektor)
Disko-Modus
Gehirn-Swap (Erlaubt Tausch mit anderen Körpern mit Gehirn-Swap)
Micro-Deassembler
Durch-Wände-Sehen-Dingens
Loot-Scanner
Notfall-Defibrilator (erlaubt wieder aufstehen nach gescheiterter Zähigkeitsprobe, einmal pro kampf)
Reflexbooster                   | ?       | ?               | ?




<!--
## TODO

- Cyberware
- Drohnen/Roboter
- Hacking-Spike (Verbrauchsgegenstand)
- Stationäre Geschütze
- Exo-Skelett
- Fahrzeuge
- AIs
- Firewalls
-->





