# Kampf

## Reihenfolge

Alle Charaktere handeln zeitgleich. Dies wird gehandhabt, indem die Dauer der Aktionen aller Charaktere festgehalten werden. Sobald die Aktion eines Charakters beendet ist, kann dieser seine nächste Aktion durchführen. Während diese Aktion läuft, führen andere Charaktere ebenfalls ihre Aktionen durch und beginnen gegebenenfalls neue Aktionen.

Die Dauer einer Aktion wird in Ticks gemessen, wobei ein Tick etwa eine 1/2 Sekunde darstellt. Für jede Aktion ist eine Dauer in Ticks festgelegt. Der Charakter, der aktuell am wenigsten Ticks hat, kann eine Aktion durchführen. Die Aktionsdauer wird auf die Tickzeit des Charakters addiert. Es ist möglich, dass ein Charakter mehrere kurze Aktionen hintereinander ausführt, während ein anderer Charakter eine einzelne, lange Aktion durchführt. Betrifft die Aktion den Charakter selbst oder andere Akteure (z.B. Bewegung oder Angriffe), so wird der Effekt am Anfang der Tickzeit ausgelöst. Bei Aktionen die die Umgebung betreffen (z.B. Tür öffnen), wird der Effekt am Ende der Tickzeit ausgelöst.

<!--
### Team-Aktionen

Team-Aktionen können von mehr als einer Person durchgeführt werden, und erlauben koordinierte Aktionen durchzuführen, wie ein taktischer Eingang oder Deckungsfeuer.

Team-Aktionen werden unterteilt in einen Setup-Teil und den Team-Teil. Ein Charakter agiert als **Initiator**, und führt den Setup durch. Dies dauert eine gewisse Anzahl Ticks, je nach Team-Aktion. Während des Setups können andere Charakter der Aktion als **Mitwirkende** beitreten. Der Initiator kann auch nach Abschluss des Setups den Team-Teil herauszögern, um anderen Team-Mitgliedern das Beitreten zu ermöglichen. Wenn der Setup abgeschlossen ist und der Initiator den Team-Teil beginnt, agieren alle beteiligten Charaktere gemeinsam. Danach ist die Team-Aktion beendet.

#### Aufteilung der Aktionen und optionale Bestandteile

Je nach Team-Aktion ist gekennzeichnet ob eine Aktion nur vom Initiator (I), von Mitwirkenden (M) oder von Allen (A) durchgeführt wird. Team-Aktionen können auch optionale Bestandteile haben, die von Mitwirkenden durchgeführt werden können. Diese sind je nach Aktion unterschiedlich, und generell gekennzeichnet durch die Anzahl an Charakteren gekennzeichnet, die diese Aktion mindestens bis maximal durchführen können.

::: {.accordion data-title="Beispiel"}

> <table><colgroup>
          <col style="width: 22%">
          <col style="width: 12%">
          <col style="width: 65%">
          </colgroup><tr><td>Taktischer Eingang</td><td>3+|5</td><td>(I) Tür öffnen und (A) hindurchgehen. Optional (1) Schild, (1-2) Deckungsfeuer und (1+) Granaten</td></tr></table>

Der Setup-Teil dieser Aktion dauert mindestens 3 Ticks und kann beliebig verlängert werden, um Charakteren die Möglichkeit zu geben, der Team-Aktion beizutreten. Danach dauert der Team-Teil genau 5 Ticks für alle Beteiligten, unabhängig davon was genau getan wird.

In dieser Aktion öffnet der Initiator (I) die Tür, und alle Beteiligten (A), also Initiator und Mitwirkende, gehen durch die Tür. Während der Initiator die Tür öffnet, können von den Mitwirkenden genau 1 Charakter mit einem Schild nach vorn treten um den Charakteren Deckung zu geben, 1-2 Charaktere können Deckungsfeuer geben, und beliebig viele Charaktere können Granaten werfen. Dies passiert alles gleichzeitig während des Team-Teils.
:::
-->

## Bewegung und Zonen

Der Bereich in dem gekämpft wird, wird in **Zonen** unterteilt. Zonen stellen größere Bereiche dar, z.B. einzelne Gägne, Räume, oder Teile von Räumen. Zonen können auch dynamisch entstehen, z.B. kann eine Rauchgranate eine neue, mit Rauch gefüllte Zone erzeugen, nur für eine begrenzte Zeit existiert.

Innerhalb einer Zone können sich Charaktere positionieren, z.B., in dem sie Deckung suchen, flankieren oder zu einem Engpass, z.B. einer Tür, gehen.

## Angriffe

### Ablauf

1. Treffer
2. Trefferzone
3. Rüstung

### Treffer

Um einen Gegner zu treffen, muss sich das Ziel in Reichweite befinden und eine der Waffe entsprechende Fähigkeitsprobe durchgeführt werden. Bei Schusswaffen müssen so viele Erfolge erzielt werden, wie der Gegner Deckung hat. Bei Nahkampf hängt die Schwierigkeit von der Aktion ab.

#### Deckung

Deckung          | Wert | Beispiele
-----------------|------|--------------------
Leichte Deckung  | 1    | Stuhl, Topfpflanze
Mittlere Deckung | 2    | Schreibtisch
Hohe Deckung     | 3    | Wand

Dieser Deckungswert geht davon aus, dass der Charakter Aktionen macht, die außerhalb der Deckung Auswirkung haben, z.B. selbst schießt. Ist dies nicht der Fall, erhält der Charakter +1 Deckung.

Sprintende Charaktere haben 1 Deckung, wenn der Winkel zwischen Laufrichtung und Schusslinie mehr als 45° beträgt.

Charaktere, die sich innerhalb in der Nähe des Schützen aus befinden, können Nahkampfdeckung haben. Die genaue Entfernung für Nahkampfdeckung hängt von der Reichweite der Waffe ab, der Deckungswert von der Nahkampffähigkeit des Ziels.

<!--Range: (6 → 2, 12 → 3, 18 → 5, Unendlich → 6)-->
<!--Deckung: (1,2 → 1; 3,4 → 2; 5,6 → 3)-->

Andere Charaktere können ebenfalls als Deckung benutzt werden, aber nur sofern diese keine Deckung haben. Die Deckung entspricht dann der Rüstung des Charakters + 1. Wenn ein Angreifer das Ziel hinter der Deckung verfehlt, wird das Ergebnis des Wurfs mit Schwierigkeit 0 gegen den Deckung gebenden Charakter verwendet.

### Trefferzone

Um die Trefferzone zu bestimmen, wird vor der Fähigkeitenprobe eine Trefferzone festgelegt. Diese erhöht die benötigten Erfolge, um genau diese Trefferzone zu treffen, in Abhängigkeit von der gewählten Trefferzone. Schnelle Schüsse gehen immer Richtung Mittelpunkt des Gegners.

#### Trefferzonen Schwierigkeit

Körperteil | Schwierigkeit
-----------|---------------
 Kopf      | +2
 Gliedmaße[¹](#trefferzone-1)| +1
 Torso     | +0

::: {#trefferzone-1}
_¹ Bei Gliedmaßen muss vorab entschieden werden, ob Beine oder Arme anvisiert werden. Es kann festgelegt werden, welches Bein anvisiert wird, oder ob der Waffenarm anvisiert wird. Alternativ kann auch ausgewürfelt werden ob links oder rechts getroffen wird._
:::

Werden genug Erfolge erzielt, um den Gegner zu treffen, aber nicht genug um die Trefferzone zu treffen, wird statt dem anvisierten Körperteil der Torso getroffen.

#### Würfel für zufälligen Treffer

Fähigkeitsstufe | Würfel
----------------|----------------
 ≤ 1            | d20
 2              | d12
 3              | d10
 4              | d8
 5              | d6
 6+             | d4

#### Auswertung eines zufälligen Treffers

Wert | Körperteil
:---:|:----------:
  1  | Kopf
  2  | Torso
  3  | Torso
  4  | R. Arm
  5  | L. Arm
  6  | Torso
  7  | R. Bein
  8  | L. Bein
  9  | R. Arm
  10 | L. Arm
  11 | R. Bein
  12 | L. Bein
  13 | R. Arm
  14 | L. Arm
  15 | R. Arm
  16 | L. Arm
  17 | R. Bein
  18 | L. Bein
  19 | R. Bein
  20 | L. Bein

_Bei Linkshändern werden R. Arm und L. Arm ausgetauscht_

### Rüstung

Wird ein durch Rüstung geschütztes Körperteil getroffen, wird der erhaltene Schmerz um den Rüstungswert reduziert. Der Schmerz kann dadurch auch komplett negiert werden.