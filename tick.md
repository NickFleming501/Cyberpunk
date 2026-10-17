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
Hinlegen           | 2      | Gibt +3 Vorteil auf Schüsse, aber Nahkampfdeckung für nahe Ziele ist um 1 erhöht, erfordert Aufstehen
Aufstehen          | 2      | Aufstehen aus dem Liegen
Disengage          | 2\|3    | Positionieren bzw. Bewegung aus einem Nahkampf heraus (weg von einem Nahkämpfer). Erfordet eine erfolgreiche Athletik-Probe, Schwierigkeit ist Erfolge(Nahkampf) des Nahkämpfers. Bei mehreren Nahkämpfern zeählt nur der höchste Nahkampf-Wert.

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

Aktion                                 |Dauer             | Beschreibung
-------------------|-----------|----------------------------------------------------
Gegenstand Fallen lassen               | 0                | Gegenstand oder Waffe fallenlassen.
Gegenstand Aufheben                    | 3                | Gegenstand oder Waffe aufheben. Gegenstand ist danach sofort verwendbar.
Gegenstand Werfen                      | 2                | Gegenstand oder Waffe auf ein Ziel werfen. Reichweite ist 1 + Athletik/2 (aufgerundet) Zonen.
Gegenstand benutzen                    | siehe Gegenstand | Benutzung eines Gegenstands, z.B. Spritzen o.ä.
Waffe ziehen (Holster)                 | 1                | Waffe aus einem Holster (z.B. am Gürtel) ziehen.
Waffe ziehen (Versteckt)               | 2                | Eine versteckte Waffe ziehen.
Waffe wegstecken                       | 1                | Waffe wieder wegpacken
Gegenstand aus Gürtel/Weste hervorholen| 1                | Leicht erreichbare Gegenstände hervorholen.
Gegenstand aus Rucksack hervorholen    | 10               | Schwer erreichbare Gegenstände hervorholen. Dauert mehrere Runden.

## Schusswaffen

Schüsse werden mit Schusswaffen geworfen und erfordern eine Schusswaffe.

Aktion                 | Dauer       | Beschreibung
-----------------------|-------------|--------------------------------------------------------
Schnelles Anvisieren   | 1           | Die Waffe auf ein (neues) Ziel richten. Erhöhrt Schwierigkeit des nächsten Schuss um 1.
Schneller Schuss/Salve | Schnell     | Schuss in die grobe Richtung des Gegners, trifft ein zufälliges Körperteil. Schwierigkeit = Deckung + 1
Ziel anvisieren        | 2           | Die Waffe auf ein (neues) Ziel richten.
Gezielter Schuss/Salve | Langsam     | Schwierigkeit = Deckung + (Kopf=2, Arm/Bein=1, Torso=0). Ein knapper Fehlschlag trifft den Torso, wenn genug Erfolge dafür erzielt wurden.
Wache                  | 2+          | Einnehmen der Wachposition dauert 2 Ticks. Danach kann zu einem beliebigen Zeitpunkt in den bewachten Bereich geschossen (Schnell oder gezielt) werden, ohne anvisieren zu müssen. Die Wache kann jederzeit abgebrochen werden.
Magazin wechseln       | Langsam/2  | Füllt Ladungen wieder auf, kann optional Munitionstyp wechseln.

<!--
Sperrfeuer             | 5+          | Deckt einen Bereich mit Sperrfeuer ab. Aus allen Zielen im Bereich des Sperrfeuers, die sich nicht in Deckung befinden, wird alle 5 Ticks ein zufälliges Ziel an einem zufälligen Körperteil getroffen. Alle Aktionen von Gegnern, die sich in Deckung befinden, werden um 1 erschwert, bei einem Fehlschlag erleiden diese einen zufälligen Treffer. Erfordert eine Waffe mit Tick-Malus kleiner gleich 4. Gegner im Bereich des Sperrfeuers bekommen einmalig 1 Stress.
-->

## Nahkampf

Nahkampfangriffe werden mit Nahkampf geworfen und erfordern eine Nahkampfwaffe.

Aktion                 | Dauer       | Beschreibung
-----------------------|-------------|--------------------------------------------------------
Schneller Angriff      | Schnell     | Trifft ein zufälliges Körperteil. Schwierigkeit ist 0 bei einem Überraschungsangriff, sonst 2
Gezielter Angriff      | Langsam     | Trifft ein gezieltes Körperteil. Schwierigkeit ist 0 bei einem Überraschungsangriff, sonst 1 + (Kopf=2, Arm/Bein=1, Torso=0). Ein knapper Fehlschlag trifft den Torso, wenn genug Erfolge dafür erzielt wurden.
Schwerer Angriff       | Langsam     | Trifft ein zufälliges Körperteil. Schwierigkeit ist 0 bei einem Überraschungsangriff, sonst 2. Verursacht doppelten Schaden, Rüstung wird, sofern vorhanden, als 1 höher behandelt. Verbraucht **1 Stamina**
Lücken-Angriff         | Schnell     | Trifft ein zufälliges Körperteil. Schwierigkeit ist 0 bei einem Überraschungsangriff, sonst 2. Getragene Rüstung wird ignoriert. Verbraucht **1 Stamina**
Konter                 | Schnell     | Kann bei gegnerischen Nahkampftreffer durchgeführt werden, auch wenn der Charakter nicht am Zug ist. Verbraucht **1 Stamina**. Schwierigkeit entspricht \#Gegnererfolge. Bei Erfolg wird der Schaden des Konters berechnet, und vom Schaden des Nahkampftreffers abgezogen. Übriger Konterschaden geht gegen ein zufälliges Körperteil des Gegners
Waffe werfen           | Schnell     | Wirft die Nahkampfwaffe auf ein zufälliges Körperteil. Reichweite ist 1 + Athletik/2 (aufgerundet) Zonen, Schwierigkeit ist Deckung + 2. Verwendet Nahkampf
Tackle                 | 2 + Waffe   | Dauer entspricht Sprint + Angriff, Angreifer bewegt sich bis zu 3/2 Felder zum Ziel und führt zusätzlich einen Nahkampfangriff aus. Ist das Ziel in Verteidigungsstellung gibt es Nachteil -1, ansonsten Vorteil +1. Benötigt **1 Stamina**
Verteidigungsstellung  | 3           | Einnehmen einer Verteidigungsstellung gegenüber einem Ziel, gibt dem Angreifer einem -1 Nachteil.

<!--
Entwaffnen            | 5 + Waffe  | Den Gegner entwaffnen. Schwierigkeit +2. Verbraucht **1 Stamina**. Bei Fehlschlag kann ggf. ein normaler Nahkampftreffer gelandet werden, wenn dafür genug Erfolge erzielt wurden.
Knockout              | 10 + Waffe | Den Gegner ausknocken, oder direkt töten. Schwierigkeit +3. Wahlweise tödlich oder nur KO. Verbraucht **1 Stamina**. Bei Fehlschlag kann ggf. ein normaler Nahkampftreffer gelandet werden, wenn dafür genug Erfolge erzielt wurden.
-->

## PSI

PSI-Aktionen werden mit Konzentration, Fühlen oder Manipulieren geworfen. PSI-Aktionen mit Fühlen- oder Manipulieren-Probe erfordern ein PSI-Implantat, PSI-Aktionen mit Konzentrationsprobe können von jedem durchgeführt werden.

Aktion                             | Dauer    | Fähigkeit | Beschreibung
-----------------------------------|----------|-----------|---------------------------------------------
Tief durchatmen                    | 3        | K[¹](#PSI-tick-1)        | Reduziert Stress um die Anzahl an Erfolgen einer Konzentrationsprobe
Mentale Gegenwehr                  | 3        | K[¹](#PSI-tick-1)        | Kann bei gegnerischen PSI-Treffer eingesetzt durchgeführt werden, auch wenn der Charakter nicht am Zug ist. Verbraucht **1 Fokus**. Reduziert die Erfolge des Gegners um die Erfolge des Konzetrationswurfes. Nur möglich, wenn Intuition größer als die Heimlichkeit des PSI-Verstärker des Angreifers ist.
Vorahnung                          | x1       | F         | Gibt Erfolge(Fühlen) Deckung (additiv) für die nächsten 3 Aktionen, sowie die selbe Anzahl an Nachteil für Nahkampfangreifer. Verbraucht **1 Fokus**
Wahrnehmung übernehmen             | x1+      | F         | Schwierigkeit = Gegenerfolge(Wille), wenn erfolgreich, dann kann der Übernehmende alles wahrnehmen, was das Ziel wahrnimmt, anstelle der eigenen Wahrnehmung. Während die Wahrnehmung übernommen ist, können andere Aktionen durchgeführt werden
Verwirren                          | x1       | M         | Schwierigkeit = Gegenerfolge(Wille), wenn erfolgreich bekommt Ziel 2 Nachteil auf alle Würfe während der nächsten 2 Aktionen. Keine Mentale Gegenwehr möglich.
Stress verursachen                 | x1       | M         | Schwierigkeit = Gegenerfolge(Wille), wenn erfolgreich bekommt Ziel (Erfolge-Gegenerfolge(Wille))+1 Stress. Verbraucht **1 Fokus**
Betäuben                           | x1       | M         | Tickzeit des Ziels wird um 6 erhöht, + 2 für jeden Krit. Verbraucht **1 Fokus**
Aktionen erzwingen                 | x3       | M         | Schwierigkeit = Gegenerfolge(Wille), wenn erfolgreich kann der Angreifer die nächsten 2 (Tick)Aktion des Ziels festlegen, jeder zusätzliche Erfolg erlaubt 1 weitere Aktion zu spezifizieren. Verbraucht **1 Fokus**

::: {#PSI-tick-1}
_¹ ist ohne PSI-Implantat oder -Verstärker möglich._
:::

<!--
## Team-Aktionen

Setup-Anteil | Team-Anteil

Aktion             | Dauer     | Beschreibung
-------------------|-----------|--------------------------------------------------------
Taktischer Eingang | 3+\|5      | (I) Tür öffnen und (A) hindurchgehen. Optional (1-2) Deckungsfeuer, (1+) Granaten und (1) Schild
Deckungsfeuer      | 3+\|3+     | (I) Wache und (M) Bewegung außerhalb des Wachbereichs, mit Deckung + 1.
-->

## Taktik

Taktische Aktionen werden mit Taktik geworfen.

Aktion                      | Dauer               | Beschreibung
----------------------------|---------------------|-------------------------------------------------------
Deckungsangriffe            | Schnell+            | Erfordert eine Waffe. Angriffe von Gegnern innerhalb der direkten Waffenreichweite gegen einen bestimmten Verbündeten werden erschwert: Deckung ist mindestens Erfolge(Taktik)/2 (aufgerundet). Verbraucht **1 Stamina**
Schwachstelle erkennen      | 2                   | Gibt Verbündeten in Rufweite 1+Erfolge(Taktik)/2 (aufgerundet) Vorteil auf die nächste offensive Aktion gegen einen bestimmten Gegner
Antreiben                   | 2                   | Reduziert die verbleibende Tick-Dauer der aktuellen Aktion eines Verbündeten in Rufweite um 3 + Erfolge(Taktik)/2 (aufgerundet), aber höchstens bis auf 1 Tick. Verbraucht **1 Fokus**
Warnruf                     | 1                   | Kann bei einer Aktion eines Gegners gegen einen Verbündeten in Rufweite durchgeführt werden, auch wenn der Charakter nicht am Zug ist. Der Angreifer erhält 1 + Erfolge(Taktik) Nachteil auf die Aktion. Verbraucht **1 Fokus**. Nicht gegen PSI-Aktionen einsetzbar.

## Verschiedenes

Aktion                      | Dauer               | Beschreibung
----------------------------|---------------------|--------------------------------------------------------
Drohne steuern              | Aktion + 1/Drohne   | Eine oder mehrere verknüpfte Drohnen führen dieselbe Aktion aus (Ziele bzw. Zonen können unterschiedlich sein). Dauer ist die längste Aktion der Drohnen, +1 für jede Drohne nach der ersten. Angriffe während Wache der Drohne funktionieren sind auch ohne direkte Kontrolle möglich. Mögliche Aktionen: _Bewegen, Positionieren, Klettern, Anvisieren (schnell und normal), Schneller und Gezielter Schuss, Wache, Schneller und Gezielter Angriff, Interaktion_
Drohnenschwarm teilen/einen | 2                   | Teilt bzw. vereint einen Drohnenschwarm. Jeder Teil des Schwarms bindet **1 Fokus**
Fenster öffnen/schließen    | 4                   | Öffnen, aber ohne das Fenster zu beschädigen
Fenster einschlagen         | 2                   | Schneller öffnen, lässt sich aber nicht wieder schließen.
Tür öffnen                  | 6                   | Eine nicht verschlossene Tür aufstoßen.
Tür eintreten               | 3                   | Eine verschlossene Tür auftreten. Erfordert Athletikprobe mit Schwierigkeit abhängig von der Türstärke. Verbraucht **1 Stamina**
Interaktion                 | ~                   | Abhängig von der Interaktion
Ausruhen                    | 5                   | Regeneriert 1 Stamina ODER 1 Fokus
Überanstrengen              | 1                   | Regeneriert 1 Stamina ODER 1 Fokus. Verursacht 1 Schmerz
Erweiterungen umschalten    | 3                   | Schaltet einen spezialisierten Gegenstand zwischen zwei Erweiterungssets um.
Superkondensator aktivieren | 1                   | Aktiviert die inaktiven Erweiterungen des Superkondensator-Boost

