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

## Eigenschaften

### Auffälligkeit

Viele Gegenstände besitzen einen Auffälligkeitswert. Dieser beschreibt, welches Aufsehen die Waffe bei anderen Personen erregen, die den Umgang mit Waffen gewohnt sind, z.B., Gang-Mitglieder, andere Söldner oder Sicherheitskräften. Dies wirkt sich vorallem darauf aus, wie schnell [Verdacht](#verdacht) steigt.

Auffälligkeit           | Wert | Beispiel         | Beschreibung 
------------------------|------|------------------|---------------------------------------------------------------------
Integriert / Getarnt    | -0.5 | Gehstock-Pistole | Der Gegenstand ist in etwas anderem verborgen, z.B. in einem unauffälligem Gegenstand oder in einem Cyborg-Teil. Ein Integrierter Gegenstand wird auch bei einem Sicherheitscheck nicht gefunden (wohl aber der "behausende" Gegenstand)
Versteckt / Unauffällig | 0    | CCW Pistole      | Der Gegenstand ist generell nicht zu sehen, und kann meist nur bei einem Sicherheitscheck gefunden werden
Gewöhnlich              | 0.5  | Gewehr           | Der Gegenstand ist generell offen sichtbar, sieht für Personen die an Waffen gewöhnt sind jedoch nicht bedrohlich aus. Ein Gewöhnlicher Gegenstand kann nur gegenüber Zivilisten verborgen werden und wird ansonsten auch ohne Sicherheitscheck bemerkt.
Auffällig               | 1    | Minigun          | Der Gegenstand ist für jeden zu sehen und kann nicht von einer Person verborgen getragen werden und gleichzeitig zugreifbar sein (aber z.B. in einem großen verschlossenen Behälter). Der Gegenstand sieht illegal aus und wird entsprechend kontrolliert, und löst generell Unmut aus.

**Gesamtauffälligkeit**: Summe der Auffälligkeit aller zugreifbar getragenen Gegenstände eines Charakters, minus 0.5, Minimum 0. Bei Cyberware wird dabei nur das auffälligste Körperteil gewertet.

::: {.accordion data-title="Beispiele"}
- Gewehr (Gewöhnlich) und Weste (Gewöhnlich): 0.5 + 0.5 - 0.5 = **0,5**
- CCW Pistole (Versteckt) und Weste (Gewöhnlich): 0 + 0.5 - 0.5 = **0**
- Shotgun (Auffällig), Weste (Gewöhnlich) und zwei Cyborg-Arme (Auffällig und Gewöhnlich): 1 + 0.5 + 1 - 0,5 = **2**
- Gehstock-Pistole (Getarnt), Leichte Rüstung (Auffällig) und Cyborg-Bein (Auffällig): -0.5 + 1 + 1 - 0,5 = **1**
:::

### Kapazität

Cyborg-Körperteile, sowie Schusswaffen, Nahkampfwaffen, Rüstungen und DiMES, besitzen Kapazität für Erweiterungen. Cyborg-Körperteile brauchen dafür eine Energiequelle, die anderen Gegenstände nicht. Spezialisierte Gegenstände oder Cyborgs mit Superkondensator können inaktive Erweiterungen haben, welche keinen Effekt haben solange sie nicht aktiviert sind.

Wechsel: Spezialisierte Gegenstände können Kapazität 6|6 haben, was bedeutet das zwischen zwei Sets von 6 Kapazität hin und her geschaltet werden kann.

## Rüstung

P | Auffälligkeit | Fernkampf-Rüstung | Nahkampf-Rüstung | Körperteile
--|---------------|-------------------|------------------|--------------
A | Versteckt     | 2                 | 3                | Alle
B | Gewöhnlich    | 1                 | 2                | Torso + Kopf
C | Auffällig     | 0                 | 1                | Torso

- Körperteile: Bestimmt, welche Körperteile durch die Rüstung geschützt werden. Der Nah-/Fernkampf-Rüstungswert wird nur für diese Körperteile erhöht.
- Fernkampf-Rüstung: Erhöht den Fernkampf-Rüstungswert, der von Fernkampfangriffen abgezogen wird
- Nahkampf-Rüstung: Erhöht den Nahkampf-Rüstungswert, der von Nahkampfangriffen abgezogen wird

 Typ    | P                | Kapazität
--------|------------------|-----------
Einfach | 2x B, 2x C       | 3
Normal  | 1x A, 2x B, 1x C | 6
Gut     | 2x A, 2x B       | 10

<!--
### Exoskelett

Exoskelette können anstelle einer Rüstung getragen werden.

P | Fernkampf-Rüstung | Nahkampf-Rüstung | Kapazität | Athletik-Bonus
--|-------------------|------------------|-----------|----------------
S | Immun             | Immun            | 30        | 10
A | 3                 | 4                | 12        | 4
B | 2                 | 3                | 8         | 2
C | 1                 | 2                | 4         | 1

- Auffälligkeit: Ein Exoskelett ist immer Auffällig
- Fernkampf-Rüstung: Erhöht den Fernkampf-Rüstungswert, der von Fernkampfangriffen abgezogen wird
- Nahkampf-Rüstung: Erhöht den Nahkampf-Rüstungswert, der von Nahkampfangriffen abgezogen wird
- Kapazität: Für Erweiterungen die in das Exoskelett eingebaut sind.
- Atheltik-Bonus: Gibt Vorteil auf Athletik-Würfe bei denen das Exoskelett helfen kann.
-->

## Schusswaffen

P | Reichweite | Auffälligkeit   | Schaden | Krit-Schaden | Tick
--|------------|-----------------|---------|--------------|------
S | Unendlich  | Integriert      | 8       | 4            | 1\|2
A | Hoch       | Versteckt       | 4       | 2            | 2\|4
B | Normal     | Gewöhnlich      | 2       | 1            | 4\|8
C | Gering     | Auffällig       | 1       | 0.5          | 6\|10

- Reichweite: Reichweite im Kampf
	- Gering: Selbe oder benachbarte Zone, danach Nachteil von 2 pro weitere Zone. Nahkampfdeckung nur wenn bereits im Nahkampf verwickelt
	- Normal: Bis zu 2 Zonen entfernt (selbe Zone + 2 weitere), danach Nachteil von 2 pro weitere Zone. Nahkampfdeckung innerhalb der selben Zone
	- Hoch: Bis zu 4 Zonen entfernt (selbe Zone + 4 weitere), danach Nachteil von 1 pro weitere Zone. Nahkampfdeckung innerhalb der selben Zone
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

 Type   | P                | Kapazität
--------|------------------|-----------
Einfach | 2x B, 3x C       | 3
Normal  | 1x A, 2x B, 2x C | 6
Gut     | 2x A, 2x B, 1x C | 10
Spezial | 1x S, 2x B, 2x C | 10 oder 6\|6

### Spezialmunition

Spezialmunition sorgt kann in bestimmten Situationen für bessern Effekt. Es kann nur ein
Munitionstyp gleichzeitig aktiviert sein. Ein Wechsel des Munitionstyps dauert eine Nachladeaktion. Munition wird nicht verbraucht, muss aber für jede Waffe
separat gekauft werden.

Munitionstyp   | Effekt
---------------|--------------------------------------------------------------------
Ausbalanciert  | Erhöht die Basis-Reichweite um 1 Zone.
Wundreißer     | +1 Schaden, Rüstung wird, sofern vorhanden, als 1 höher behandelt
Panzerbrechend | Rüstung wird, sofern vorhanden, als um 1 verringert behandelt
Schock         | +2 Schaden gegen Cyborg-Körperteile / Drohnen
Leuchtspur     | +1 Vorteil (kumulativ) pro konsekutiven Schuss auf das gleiche Ziel (Start +0, Limit +2 ab dem 3. Schuss)
Kryo           | Addiert 1 Tick auf Tickzeit des Ziels

## Nahkampfwaffen

P | Auffälligkeit   | Schmerz | Krit-Schaden | Tick
--|-----------------|---------|--------------|------------
S | Integriert      | 8       | 5            | 1\|2
A | Versteckt       | 4       | 3            | 2\|4
B | Gewöhnlich      | 2       | 2            | 4\|8
C | Auffällig       | 1       | 1            | 6\|10

- Für Angriffe muss sich generell der Angreifer an das Ziel heran positionieren.
- Tick ist Wert, der auf die Tickzeit der Aktionen addiert wird.
- Tick: Anzahl an Ticks (Schnell | Langsam), die ein Angriff mit der Waffe dauert.

Rest siehe [Schusswaffen](#schusswaffen-1).

 Typ    | P                | Kapazität
--------|------------------|------------
Einfach | 2x B, 2x C       | 3
Normal  | 1x A, 2x B, 1x C | 6
Gut     | 2x A, 2x B       | 10
Spezial | 1x S, 2x B, 1x C | 10 oder 6\|6

## PSI-Verstärker

Ein PSI-Verstärker verstärkt PSI-Aktionen

P | Reichweite    | Tick | Heimlichkeit | Fühlen               | Manipulieren
--|---------------|------|--------------|----------------------|----------------------
S | Hoch          | 1    | 5            | +1 Erfolg, 2 Vorteil | +1 Erfolg, 2 Vorteil
A | Normal        | 2    | 3            | 2 Vorteil            | 2 Vorteil
B | Gering        | 3    | 2            | 0                    | 0
C | Berührung     | 4    | 1            | 1 Nachteil           | 1 Nachteil

- Reichweite
	- Berührung: Selbe Zone, danach Nachteil von 2 pro weiterer Zone
	- Gering: Selbe Zone oder benachbarte Zone, danach Nachteil von 2 pro weitere Zone
	- Normal: Selbe Zone oder benachbarte Zone, danach Nachteil von 1 pro weitere Zone
	- Hoch: Bis zu 3 Zonen entfernt (selbe Zone + 3 weitere), danach Nachteil von 1 pro weitere Zone
- Tick: Tickzeit für PSI-Aktionen im Kampf
- Heimlichkeit: Schwierigkeit für das Ziel, die PSI-Aktion zu bemerken
- Fühlen/Manipulation-Vorteil: Senkt/Erhöht die entsprechende Fähigkeit für PSI-Aktionen.

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

## Drohnen

Drohnen binden Fokus des Charakters. Ein Charakter muss pro Drone **1 Fokus** für das Kontrollieren der Drohne reservieren. Solange eine Drone kontrolliert wird, kann der entsprechende Fokus nicht verwendet werden.

P | Auffälligkeit | Bewegung   | Kapazität | Stabilität | Fähigkeitswert
--|---------------|------------|-----------|------------|----------------
S | Getarnt       | Schwarm    | 12        | 20         | 6
A | Unauffällig   | Fliegend   | 8         | 10         | 4
B | Gewöhnlich    | Kletternd  | 4         | 8          | 3
C | Auffällig     | Boden      | 2         | 4          | 2

- Bewegung:
    - Boden: Erlaubt bodengebundene, horizontale Bewegung, sowie. Treppen o.ä.
    - Kletternd: Erlaubt Bewegung entlang beliebiger Oberflächen, mit uneingeschränkter Bewegungsgeschwindigkeit.
    - Fliegend: Erlaubt Bewegung durch die Luft. Kann Nahkampf ohne Disengage verlassen.
	- Schwarm: Statt einer einzelnen Drone handelt es sich um einen kleinen Schwarm fliegender Dronen. Der Schwarm kann sich aufteilen, aber Stabilität und Fähigkeiten werden ebenfalls aufgeteilt, und jeder Teil bindet jeweils 1 Fokus.
- Kapazität: Für Erweiterungen, z.B.Eingebaute Waffe, Sicht- oder Werkzeug.
- Stabilität: Trefferpunkte der Drone. Dronen haben nur eine einzige Trefferzone und keinen Gesamtschmerz.
    - Erleidet die Drohne Schaden größergleich dem Stabilitätswert, so zählt sie als beschädigt und ist aktionsunfähig
    - Erleidet die Drohne Schaden größergleich dem doppelten Stabilitätswert. so ist sie irreperabel zerstört.
	- **Schwachpunkt**: die Drohnen hat einen Schwachpunkt der vergleichbar wie ein menschlicher Kopf durch gezielte Angriffe getroffen werden kann, was doppelten Schaden verursacht.
- Fähigkeitswert: Wert für Fähigkeiten der Drohne, wird verwendet an Stelle von Athletik, Intuition, Schusswaffen, Nahkampf, sowie für ein Werkzeug-Skill. Drohnen haben kein Stamina/Fokus.

Grundausstattung jeder Drohne:

- Jede Drohne besitzt eine Kamera, Mikrofon und Kommunikator eingebaut, die nicht von der Kapazität abgezogen werden.
- Rüstung 1 gegen Nah- und Fernkampf
- Entsprechende Bewegung ohne Würfe: Drohnen brauchen kein Parkour

 Type   | P
--------|----------------
Einfach | 2x B, 3x C
Normal  | 1x A, 2x B, 2x C
Gut     | 2x A, 2x B, 1x C
Spezial | 1x S, 2x B, 2x C

### Programme

Drohnen können außerhalb von Kämpfen einfache Programme autonom durchführen:

- **Warten**: Drohne wartet
- **Folgen**: Drohne folgt einem Charakter, wahlweise Heimlich
- **Bewegen**: Begibt sich über einen festgelegten Weg zu einem bestimmten Ort.
- **Beobachten/Erkunden**: Drohne beobachtet oder erkundet und achtet auf vorab festgelegte Details, die automatisch gemeldet werden.

## DiMES

Ein DiMES besitzt Kapazität für Erweiterungen, sonst nichts.

Typ     | Kapazität
--------|-----------
Einfach | 3
Normal  | 6
Gut     | 10
Spezial | 10 oder 6\|6 Wechselt zwischen zwei Erweiterungs-Sets

## Verbrauchsgegenstände

Verbrauchsgegenstände werden einmalig gekauft, und stehen dann während einer Mission in entsprechender Anzahl zur Verfügung. Zwischen Missionen können die Verbrauchsgegenstände kostenlos wieder aufgefüllt werden.

### Granaten

Granaten können auf Gegner geworfen werden. Bei Granaten die Schaden verursachen wird jeder Schadenspunkt zufällig verteilt (d12 Treffer)

P | Effektstärke | Radius
--|--------------|--------
A | 4            | d5+3
B | 3            | d3+1
C | 2            | d2

- Effekt:
    - Rauch: Gibt Deckung und versteckt alle Charaktere im Rauch vor Sicht (inkl. Nacht- u. Wärmesicht). Effekt gilt in beide Richtungen (in Rauch rein/heraus)
    - Fragment: Explosion
    - Spezial: Flash, AP, EMP
- Effektstärke (N):
    - Rauch*: Erhöhte Deckung (Minimum 2) & Schwierigkeit für Intuition (+2) (der Rauch selbst ist offensichtlich), hält für Effektstärke x5 Ticks
    - Fragment: x3 Schaden, Rüstung wird um 1 höher betrachtet, sofern vorhanden
    - Spezial:
        - Flash: x3 Ticks, die Charaktere ausgeknockt werden
		- EMP: x3+2 Schaden gegen Cyborgs/Drohnen, sonst 0 Schaden
        - AP: x3 Schaden, Rüstung wird um 1 niedriger betrachtet
- Radius: Es können nur Charaktere innerhalb einer Zone oder in der Nähe eines Interaktionspunktes getroffen werden. Anzahl der Charaktere die vom Effekt maximal betroffen sein können. Bei Rauchgranaten beschränkt dies die Größe der entstehenden Rauch-Zone, bei anderen Effekten ist es die maximale Anzahl betroffener Charaktere. Welche Charaktere genau getroffenen werden, wird vom Spielleiter final entschieden.

 Typ    | P
--------|------------
Einfach | 1x B, 1x C
Normal  | 2x B
Gut     | 1x A, 1x B

### Stims

Im Kampf einsetzbare Medizin/Aufputschmittel. Können auch als Tabletten, Pillen oder in anderen Formen auftreten.

 Typ    | Effektstärke
--------|------------
Gut     | 6
Normal  | 4
Einfach | 2

- Effekt
    - Stressreduktion: Reduziert Stress (nicht unter Basisstress)
    - Schmerzreduktion: Reduziert Gesamtschmerz, aber keinen Körperteilschmerz
	- Fokus-Boost: Stellt Effektstärke Fokus sofort her, auch über das Maximum heraus
	- Stamina-Boost: Stellt Effektstärke Stamina sofort her, auch über das Maximum heraus
- Effektstärke: Menge an Stress/Gesamtschmerz/Fokus/Stamina die reduziert/wiederhergestellt wird
- Aktivierung: 1 Tick

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
- Unauffälligkeit: Schwierigkeit für eine Intuitionsprobe, um die Wanze zu entdecken
- Senderadius: Bereich in dem auf die Sensoren der Wanze zugegriffen werden kann.

 Typ    | P
--------|----------------
Einfach | 2x B, 1x C
Normal  | 1x A, 1x B, 1x C
Gut     | 2x A, 1x B

## Cyberware

### Energiequelle

Typ     | Energiequelle       | Kapazität | Basisstress | Beschreibung
--------|---------------------|-----------|-------------|---------------------------------------------------------------
Einfach | Batterie            | 12        | 0.5         | Muss nach maximal 20h wieder aufgeladen werden, was bis zu 6h dauert.
Normal  | Bioreaktor          | 24        | 1           | Erzeugt Energie durch mehr Essen. Etwa 5x soviel, wie eine normale Person isst. Es gibt spezielle "Energieriegel", die besonders viele Nährstoffe für Bioreaktoren beinhalten
Gut     | Radionuklidbatterie | 32        | 1.5         | Erzeugt Energie ohne weitere Voraussetzungen. Die Batterie muss alle paar Jahre ausgetauscht werden.
Spezial | Superkondensator    | 16 \| 60   | 1\|2         | Erzeugt begrenzte Energie im Normalbetrieb, aber kann bei Bedarf für ca. 10 Minuten nahezu unbegrenzt Energie produzieren. Danach muss der Superkondensator wieder aufgeladen, was bis zu 4h dauert. Dies erlaubt selektive Aktivierung[¹](#cyber-energy-1) von zusätzlicher Cyberware. Körperteile müssen über den Normalbetrieb angeschlossen sein, für Erweiterungen wird beim Einbau entschieden ob sie Teil des Normalbetriebs sind oder nur im geboosteten Zustand aktiv sind.

::: {#cyber-energy-1}
_¹ Wenn der Superkondensator aktiviert wird, erhöht sich der Basisstress von 1 auf 2. Nach Ende des Boosts sinkt der Basisstress wieder auf 1._
:::

### Cyborg-Körperteil

P | Auffälligkeit | Rüstung | Kapazität | Basisstress
--|---------------|---------|-----------|-------------
A | Versteckt     | 1\|1     | +8        | 0
B | Gewöhnlich    | 1\|0     | +4        | 0.5
C | Auffällig     | 0\|0     | 0         | 1

- Auffälligkeit: Gilt für alle in den Körperteil eingebauten Erweiterungen
- Rüstung: Eingebaute Rüstung für Nah- bzw. Fernkampf. Bei B gibt nur Nahkampf-Rüstung
- Kapazität: Kapazität für das Körperteil (negative Kapazität senkt die Gesamtkapazität)
- Basisstress: Erhöht den Basisstress (aufgerundet)

**Ein zweites, kostenloses Körperteil (Arm/Bein) gibt weder Kapazität noch Basisstress, aber nur wenn es gleich gebaut ist!**

 Typ    | P
--------|----------------
Einfach |      2x B, 2x C
Normal  |1x A, 1x B, 2x C
Gut     |2x A, 1x B, 1x C

### Erweiterungen

Erweiterungstyp | Anwendbarkeit
----------------|-----------------------------------------
Beliebig        | Kann (nahezu) überall eingebaut werden.
Sicht           | Cyborg-Kopf, Implantat(Auge), Rüstung(Kopf), Schusswaffen, DiMES, Exoskelett, Drohne
Werkzeug        | Cyborg-Arme, DiMES, Nahkampfwaffe, Exoskelett, Drohne
Körper          | Cyborg-Komplettkörper, Rüstung, Exoskelett, Drohne
Atmung          | Cyborg-Torso, Rüstung(Kopf), Exoskelett
Spezifisch      | Hängt von genauer Verwendung ab, z.B. ein Fähigkeitsbooster für Schusswaffen kann in einer Schusswaffe eingebaut sein, ein Fähigkeitsbooster für Heimlichkeit aber nicht.
Arme            | Cyborg-Arme, Exoskelett, Drohne
Beine           | Cyborg-Beine, Exoskelett


Erweiterung                     | Kapazität | Preis | Typ               | Beschreibung
--------------------------------|-----------|-------|-------------------|-----------------------------------------------------------------------
3D-Drucker                      | -6        | 3000  | Beliebig          | Kann kleine Gegenstände mit einfacher Form herstellen, inklusive Einfacher Einweg-Waffen
Aktive Camouflage               | -10       | 5000  | Körper            | Macht den Körper transparent, solange man sich nur langsam bewegt ist man effektiv unsichtbar, aber schnellere Bewegungen oder Kampfaktionen können nicht komplett versteckt werden (-2 Nachteil für Angreifer)
Audio-Rekorder                  | -1        | 500   | Beliebig          | Erlaubt aktuelle Geräusche aufzunehmen
Auto-Ausweicher                 | -10       | 5000  | Cyborg-Körper     | Gibt eine Mindest-Deckung von 1
Automatische Blende             | -4        | 2000  | Sicht (kein DiMES) | Immunität gegen Flash
Automatische Reparatur          | -8        | 4000  | Cyborg-*          | Regeneriert nicht-kritischen Schaden an Cyborg-Körperteilen, ca. 1 Box pro Minute
Bionische Fingerspitzen         | -2        | 1000  | Cyborg-Arm        | Erlaubt es die Fingerspitzen anzupassen, sodass sie veränderbare (oder gar keine) Fingerabdrücke haben.
Bionische Stimmbänder           | -2        | 1000  | Cyborg-Kopf       | Verstellt die Stimme zu der einer anderen Person
Blackbox-Recorder               | -1        | 500   | Cyborg-Kopf       | Zeichnet Sinneswahrnehmungen auf, Aufzeichnung überlebt auch Zerstörung des entsprechended Kopfes
Brechstangenfunktion            | -2        | 1000  | Nahkampfwaffe     | Gibt +2 Vorteil auf gewaltsames Öffnen von Türen u.ä.
Datenbank                       | -1        | 500   | Beliebig          | Erlaubt extrem große Datenmengen zu speichern
Disko-Modus                     | -1        | 500   | Beliebig          | Macht Licht, bunte Farben und coole Mucke
Dokumentenscanner               | -1        | 500   | Sicht             | Ermöglicht schnell größere Mengen an Text und Dokumenten zu scannen
Druckregulator                  | -4        | 2000  | Körper (keine Drohne) | Ermöglicht Aktionen in Situationen mit sehr hohem oder sehr niedrigem Druck (z.B. Ozeantiefe oder außen an einem Flugzeugs)
Eingebaute Waffe                | -2\|-6\|-10 | 1k\|3k\|5k | Beliebig          | Erlaubt eine Versteckte\|Gewöhnliche\|Aufällige Waffe zu verbauen
Fähigkeitsbooster               | -3\|-6     | 1500\|3k  | Spezifisch        | Gibt einen +1 Vorteil auf einen bestimmten Fähigkeitswert der den Booster involviert. Booster für Kampffähigkeiten verbrauchen doppelte Kapazität. Die genaue Art des Boosters sowie die dadurch verbesserte Fähigkeit müssen bei Erwerb festgelegt werden. Beispiel: Fähigkeitsbooster für Schusswaffen könnte ein Ziellaser sein.
Gasfilter                       | -2        | 1000  | Atmung            | Filtert (giftige) Gase aus der Atemluft
Gedächtnis-Backup               | -16       | 8000  | Cyborg-Kopf       | Lagert Erinnerungen auf einen externen Speicher aus. Ermöglicht es, sich an viele Sachen zu erinnern oder sogar eine grobe Wiederherstellung des Benutzers nach Terminierung
Gehirn-Swap                     | -6        | 3000  | Cyborg-Kopf       | Erlaubt es das Gehirn zu entnehmen und in andere Körper mit Gehirn-Swap einzusetzen
Geigerzähler                    | -1        | 500   | Beliebig          | Meldet Radioaktivität
Geräuschabsorber                | -2        | 1000  | Spezifisch        | Macht Dinge leise
Gleitmembran                    | -10       | 5000  | Arme              | Erlaubt gleiten
GPS                             | -1        | 500   | Beliebig          | Erlaubt die genaue Position festzustellen
Granatmensch™                   | -10       | 5000  | Körper (keine Drohne) | Erzeugt die Explosion einer bestimmten Granate an der Position des Nutzers, ohne diesen selbst zu betreffen. Die Granate muss vor Einsatz vorbereitet werden, was ca. 2-3 Minuten dauert und die Granate verbraucht.
Hacking-Werkzeug                | -1        | 500   | Werkzeug          | Ermöglicht Software-Hacking
Holographische Maske            | -6        | 3000  | Cyborg-Kopf       | Erlaubt freies Anpassen von Gesicht
Holographische Projektion       | -6        | 3000  | Beliebig          | Erzeugt eine holographische Projektion des Benutzers an einer anderen Position, aber innerhalb der Sichtweite des Benutzers.
Infrarotsicht                   | -1        | 500   | Sicht             | Ermöglicht Sehen im Infrarotbereich
Jammer                          | -2        | 1000  | Beliebig          | Blockiert Kommunikation
Kamera                          | -1        | 500   | Sicht             | Erlaubt Fotos und Videos der aktuellen Sicht zu machen
Kletterhände                    | -4        | 2000  | Arme              | Ermöglicht klettern entlang glatter Oberflächen
Kommunikator                    | -1        | 500   | Beliebig          | Erlaubt Kommunikation mit anderen Kommunikatoren
Kraftbooster                    | -6        | 3000  | Arme              | Athletik +1, Erlaubt es sehr schwere Dinge zu heben.
Mega-Bohrer                     | -10       | 5000  | Werkzeug          | Erlaubt es, große Öffnungen in Wänden zu erzeugen. Funktioniert nur für schwächere Wände.
Micro-Deassembler               | -2        | 1000  | Beliebig          | Wandelt kleine Gegenstände in einfaches Bastelmaterial um, z.B. für einen 3D-Drucker
Multitool                       | -1        | 500   | Werkzeug          | Einfaches Werkzeug für grundlegende Hardware-Arbeiten
Nachtsicht                      | -1        | 500   | Sicht             | Erlaubt Sicht in Dunkelheit, aktiv
Neodymium-Schild                | -6        | 3000  | Cyborg-*          | +1 Rüstung
Notfall-Defibrillator           | -12       | 6000  | Beliebig (kein DiMES) | Aktiviert den Besitzer nach einer gescheiterten Zähigkeitsprobe, muss danach aber für ca. 5 Minuten wieder aufladen.
Optische Vergrößerung           | -1        | 500   | Sicht             | Erlaubt an entfernte oder kleine Dinge heranzuzoomen
Restlichtverstärker             | -1        | 500   | Sicht             | Erlaubt Sicht in Dunkelheit, passiv
Richtmikrophon                  | -1        | 500   | Sicht             | Ermöglicht Hören in Sichtlinie
Rückholvorrichtung              | -2        | 1000  | Nahkampfwaffe     | Erlaubt die Waffe aus Entfernung wieder zurückzuholen, dauert Langsam + 1 Tick pro Zone Entfernung
Sauerstoff-Tanks                | -6        | 3000  | Atmung            | Bietet Sauerstoff für ca. 10 Minuten
Scheinwerfer                    | -1        | 500   | Beliebig          | Macht helles Licht
Schmerzfilter                   | -16       | 8000  | Cyborg-Körper     | Zähigkeitsschwellen sind alle 4 Gesamtschmerz
Schockabsorber                  | -2        | 1000  | Beine             | Kein Fallschaden
Schweißbrenner                  | -6        | 3000  | Werkzeug          | Ermöglicht Metall zu schweißen
Schwimmflossen-Kit              | -2        | 1000  | Beine             | Ausfahrbare Schwimmflossen. Erlauben schnelle Unterwasserbewegung
Seilwinde                       | -2        | 1000  | Werkzeug          | Ermöglicht Abseilen oder Klettern/Hochziehen
Sprinter-Beine                  | -8        | 4000  | Beine             | Erlaubt schnelleres Sprinten. Reduziert Bewegung auf 2 Ticks
Sprung-Beine                    | -2        | 1000  | Beine             | Erlaubt große Sprünge
Stauraum                        | -1        | 500   | Beliebig          | Ermöglicht kleine Gegenstände getarnt zu verstauen
Stimmanalysator                 | -6        | 3000  | Beliebig          | Analysiert subtile Details in Stimm- und Sprachverhalten um die Täuschungen zu durchschauen
Subvocal-Kommunikator           | -2        | 1000  | Cyborg-Kopf       | Wie ein Kommunikator, aber lautlos
Temperatur-Isolierung           | -2        | 1000  | Körper            | Maskiert die Wärmestrahlung des Benutzers
Wand-Radar                      | -10       | 5000  | Sicht             | Erlaubt es durch einfache Wände oder Türen zu sehen (eine Schicht), und auch zu zielen.
Zähigkeitsbooster               | -6        | 3000  | Cyborg-*          | Zähigkeit +1










<!--
Fehlende Ideen:

Eingebaute KI
Offensiv-Injektor (Spritzt Gifte/Substanzen in andere)
Magnete
Loot-Scanner
Reflexbooster                   | ?       | ?               | ?

removed

Automatische Spritze            | 3         | Atmung            | Ermöglicht Spritzen zu laden, die bei Bedarf automatisch injiziert werden
LIDAR-Scanner                   | 1         | Sicht             | Misst Entfernung und 

-->


<!--
## TODO

- Drohnen/Roboter
- Hacking-Spike (Verbrauchsgegenstand)
- Stationäre Geschütze
- Fahrzeuge
- AIs
- Firewalls
-->





