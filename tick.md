# Aktionsdauer

Definition: **1 Tick = 1/2 Sekunde**

## Bewegung

Aktion             | Dauer  |Beschreibung
-------------------|--------|--------------------------------------------------------
Bewegen            | 3      | Bewegung in eine angrenzende Zone
Positionieren      | 2      | Bewegung zu einem bestimmten Punkt in der aktuellen Zone, z.B. Deckung, Engpass, Interaktionspunkt
Schleichen         | 5      | Heimliche Bewegung zu einem bestimmten Punkt in der aktuellen Zone oder einer angrenzenden Zone
Klettern           | 8      | Unter Dingen hindurch kriechen oder darüber klettern.
In die Hocke gehen | 1      | Gibt +1 Vorteil auf Schüsse
Hinlegen           | 2      | Gibt +3 Vorteil auf Schüsse, erfordert Aufstehen
Aufstehen          | 2      | Aufstehen aus dem Liegen

<!--
Aktion             | Dauer  |Beschreibung
-------------------|-----------|--------------------------------------------------------
Sprinten           | 3–5    | Bewegung um 3/2 (Kardinal/Diagonal) Felder. Dauer ist 6-⎡Athletik/2⎤ (1,2 → 5; 3,4 → 4; 5,6 → 3). Gibt Deckung 1 vor seitlichen Schüssen. Verbraucht **1 Stamina**
Gehen              | 2/3    | Kardinal/Diagonal pro Feld.
Schleichen         | 5/7    | Kardinal/Diagonal pro Feld. Schleichen ist lautlos.
Kriechen/Klettern           | 10   | Under Dingen hindurchkriechen oder darüber klettern, Leitern hoch- oder runterklettern, etc. Verbraucht **1 Stamina**
In die Hocke gehen | 4      | Gibt einen +1 Vorteil auf Schüsse
Hinlegen           | 8     | Gibt einen +3 Vorteil auf Schüsse
Aufstehen (Hocke)  | 4      |
Aufstehen (Liegen) | 8     |
In Deckung gehen   | 5      | Erhöht Deckungswert einmalig um 1, bis der Charakter die Deckung verlässt
-->

## Gegenstände

Aktion                                 |Dauer                 |Beschreibung
-------------------|-----------|--------------------------------------------------------
Gegenstand Fallen lassen               | 0                    | Gegenstand oder Waffe fallenlassen.
Gegenstand Aufheben                    | 3                    | Gegenstand oder Waffe aufheben. Gegenstand ist danach sofort verwendbar.
Gegenstand Werfen                      | 2                    | Gegenstand oder Waffe auf ein Ziel werfen. Reichweite ist (6 + Athletik)
Gegenstand benutzen                    | siehe Gegenstand     | Benutzung eines Gegenstands, z.B. Spritzen o.ä.
Waffe ziehen (Holster)                 | 1                    | Waffe aus einem Holster (z.B. am Gürtel) ziehen.
Waffe ziehen (Versteckt)               | 2                    | Eine versteckte Waffe ziehen.
Waffe wegstecken                       | 1                    | Waffe wieder wegpacken
Gegenstand aus Gürtel/Weste hervorholen| 4                    | Leicht erreichbare Gegenstände hervorholen.
Gegenstand aus Rucksack hervorholen    | 10                   | Schwer erreichbare Gegenstände hervorholen. Dauert mehrere Runden.

## Schusswaffen

Aktion                 |Dauer        | Beschreibung
-----------------------|-------------|--------------------------------------------------------
Schnelles Anvisieren   | 1           | Die Waffe auf ein (neues) Ziel richten. Erhöhrt Schwierigkeit des nächsten Schuss um 1.
Schneller Schuss/Salve | Schnell     | Schuss in die grobe Richtung des Gegners, trifft ein zufälliges Körperteil. Schwierigkeit = Deckung + 1
Ziel anvisieren        | 2           | Die Waffe auf ein (neues) Ziel richten.
Gezielter Schuss/Salve | Langsam     | Schwierigkeit = Deckung + (Kopf=2, Arm/Bein=1, Torso=0)
Sperrfeuer             | 5+          | Deckt einen Bereich mit Sperrfeuer ab. Aus allen Zielen im Bereich des Sperrfeuers, die sich nicht in Deckung befinden, wird alle 5 Ticks ein zufälliges Ziel an einem zufälligen Körperteil getroffen. Alle Aktionen von Gegnern, die sich in Deckung befinden, werden um 1 erschwert, bei einem Fehlschlag erleiden diese einen zufälligen Treffer. Erfordert eine Waffe mit Tick-Malus kleiner gleich 4. Gegner im Bereich des Sperrfeuers bekommen einmalig 1 Stress.
Wache                  | 2+          | Einnehmen der Wachposition dauert 2 Ticks. Danach kann zu einem beliebigen Zeitpunkt in den bewachten Bereich geschossen (Schnell oder gezielt) werden, ohne anvisieren zu müssen. Die Wache kann jederzeit abgebrochen werden.
Magazin wechseln       | Langsam/2  | Füllt Ladungen wieder auf, kann optional Munitionstyp wechseln.

## Nahkampf

Aktion                 |Dauer        | Beschreibung
-----------------------|-------------|--------------------------------------------------------
Schneller Angriff      | Schnell     | Schwierigkeit ist 0 bei einem Überraschungsangriff, sonst 2
Gezielter Angriff      | Langsam     | Schwierigkeit ist 0 bei einem Überraschungsangriff, sonst 1
Schwerer Angriff       | Langsam     | Schwierigkeit ist 0 bei einem Überraschungsangriff, sonst 2. Verursacht doppelten Schmerz. Benötigt **1 Stamina**
Konter                 | Schnell + 2 | Kann vor Gegnerangriff durchgeführt werden, auch wenn der Charakter nicht am Zug ist. Schwierigkeit entspricht \#Gegnererfolge+1. Schaden ist dann (A-B)-1, nicht negativ.



Entwaffnen            | 5 + Waffe  | Den Gegner entwaffnen. Schwierigkeit +2. Verbraucht **1 Stamina**. Bei Fehlschlag kann ggf. ein normaler Nahkampftreffer gelandet werden, wenn dafür genug Erfolge erzielt wurden.
Knockout              | 10 + Waffe | Den Gegner ausknocken, oder direkt töten. Schwierigkeit +3. Wahlweise tödlich oder nur KO. Verbraucht **1 Stamina**. Bei Fehlschlag kann ggf. ein normaler Nahkampftreffer gelandet werden, wenn dafür genug Erfolge erzielt wurden.
Verteidigungsstellung | 3          | Einnehmen einer Verteidigungsstellung gegenüber einem Ziel, erhöht die Schwierigkeit für den Angreifer um 1
Tackle                | 2 + Waffe  | Dauer entspricht Sprint + Angriff, Angreifer bewegt sich bis zu 3/2 Felder zum Ziel und führt zusätzlich einen Nahkampfangriff aus. Ist das Ziel in Verteidigungsstellung gibt es Nachteil -1, ansonsten Vorteil +1. Verbraucht **1 Stamina**

## PSI

Aktion                             | Dauer    | Fähigkeit |Beschreibung
-----------------------------------|----------|-----------|---------------------------------------------
Generisches Einfühlen/Manipulieren | x1/x2/x3 | F/M       | Einfache/Mittlere/Schwere Aktionen
Konzentrieren                      | 3[¹](#PSI-tick-1)       | K         | Stress abbauen, Manipulation erschweren oder umkehren, Bestimmte Aufgaben erleichtern.
Stress verursachen                 | x1       | M         | Ziel bekommt (Erfolge-Gegenerfolge(Wille))+1 Stress (nur wenn Erfolge > Gegenerfolge)
Wahrnehmung übernehmen             | x1+      | F         | Schwierigkeit = Gegenerfolge(Wille), wenn erfolgreich, dann kann der Übernehmende alles wahrnehmen, was das Ziel wahrnimmt
Körper Übernehmen                  | x2+      | M         | Schwierigkeit = 2+Gegenerfolge(Wille), wenn Erfolgreich, dann ist Gegner übernommen und agiert nach Anweisung des Übernehmenden. Verbraucht **1 Fokus**
Betäuben                           | x2       | M         | Tickzeit des Ziels wird um 6+Erfolge*3 erhöht. Verbraucht **1 Fokus**
Falsche Wahrnehmung                | x3       | M         | Schwierigeit = 1+Gegenerfolge(Wille), wenn Erfolgreich dann nimmt das Ziel eine leicht andere Situation[²](#PSI-tick-2) war. Verbraucht **1 Fokus**
Aktionen erzwingen                 | x2       | M         | Schwierigkeit = Gegenerfolge(Wille), wenn erfolgreich kann der Angreifer die nächsten 2 (Tick)Aktion des Ziels festlegen, jeder zusätzliche Erfolg erlaubt 1 weitere Aktion zu spezifizieren.

::: {#PSI-tick-1}
_¹ Konzentrieren ist ohne PSI-Implantat oder -Verstärker möglich und hat konstante Dauer._
:::

::: {#PSI-tick-2}
_² Z.B. eine Person an einer anderen Position, etwas/jemand nicht da, mehr Gegner, etc._
:::

<!--
## Team-Aktionen

Setup-Anteil | Team-Anteil

Aktion             | Dauer     | Beschreibung
-------------------|-----------|--------------------------------------------------------
Taktischer Eingang | 3+\|5      | (I) Tür öffnen und (A) hindurchgehen. Optional (1-2) Deckungsfeuer, (1+) Granaten und (1) Schild
Deckungsfeuer      | 3+\|3+     | (I) Wache und (M) Bewegung außerhalb des Wachbereichs, mit Deckung + 1.
-->

## Verschiedenes

Aktion                     | Dauer               | Beschreibung
---------------------------|---------------------|--------------------------------------------------------
Fenster öffnen/schließen   | 4                   | Öffnen, aber ohne das Fenster zu beschädigen
Fenster einschlagen        | 2                   | Schneller öffnen, lässt sich aber nicht wieder schließen.
Tür öffnen                 | 6                   | Eine nicht verschlossene Tür aufstoßen.
Tür eintreten              | 3                   | Eine verschlossene Tür auftreten. Erfordert Athletikprobe mit Schwierigkeit abhängig von der Türstärke. Verbraucht **1 Stamina**
Interaktion                | ~                   | Abhängig von der Interaktion
Ausruhen                   | 5                   | Regeneriert 1 Stamina ODER 1 Fokus
Überanstrengen             | 1                   | Regeneriert 1 Stamina ODER 1 Fokus. Verursacht 1 Schmerz

