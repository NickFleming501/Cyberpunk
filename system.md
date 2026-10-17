# System

## Attribute

Attribute definieren den Charakter indem sie die Resistenz und Flexibilität von Körper und Geist
beschreiben. Attribute dienen als Basis für spezielle Würfe und werden ähnlich zu Checks von
Fähigkeiten gehandhabt.

  Attribut  |              Beschreibung
:----------:|:----------------------------------------:
Zähigkeit   |      Körperliche Resistenz, Stamina
Wille       |            Mentale Resistenz
Athletik    |      Bewegungsfähigkeit und Stärke
Intuition   | Wahrnehmung und Reaktionsgeschwindigkeit

### Zähigkeit

Zähigkeit stellt die körperliche Resistenz des Charakters dar. Charaktere müssen Zähigkeitsproben bestehen, um starken Schmerzen widerstehen zu können oder um in physisch anstrengenden Situationen durchzuhalten.

### Wille

Wille stellt die mentale Resistenz des Charakters dar. Charaktere müssen Willensproben bestehen, um mentale Anstrengungen zu überwinden. Dies können beispielsweise Situationen sein, in denen der Charakter ein hohes Stresslevel erreicht, oder sich gegen Beeinflussung in Gesprächen oder mentale Angriffe behaupten muss.

### Athletik

Athletik stellt die körperliche Beweglichkeit und Stärke eines Charakters dar.

Ein Charakter hat ⎣Athletik/2⎦+1 **Stamina** (1 → 1, 2,3 → 2, 4,5 → 3, 6 → 4), die für bestimmte Aktionen verbraucht werden. Ausruhen regeneriert verbrauchte **Stamina** wieder.

### Intuition

Intuition stellt die Wahrnehmung und geistige Kraft eines Charakters dar.

Ein Charakter hat ⎣Intuition/2⎦+1 **Fokus** (1 → 1, 2,3 → 2, 4,5 → 3, 6 → 4), die für bestimmte Aktionen verbraucht werden. Ausruhen regeneriert verbrauchte **Fokus** wieder.

## Fähigkeiten

Alle Fähigkeiten werden in Fähigkeitsstufen unterteilt:

- 1
- 2
- 3
- ...

### Basisfähigkeiten

Alle Charaktere besitzen ein gewisses Maß an Basisfähigkeiten (Kompetenz), die nicht explizit erwähnt werden müssen.

### Probe

In einer Situation in der Zweifel über das Auskommen einer versuchten Handlung eines Charakters bestehen wird eine Probe durchgeführt.

Proben außerhalb eines Kampfes können nicht wiederholt werden, Proben im Kampf können nach Ablauf der Tickzeit wiederholt werden.

#### Schwierigkeit

Jede Probe besitzt eine Schwierigkeit, die angibt, wie viele Erfolge mindestens erzielt werden müssen, um einen Fehlschlag zu vermeiden.

#### Wurf

Gemäß der Fähigkeitsstufe des Charakters werden folgende Würfel geworfen:

- 1: d4
- 2: d4 und d6
- 3: d4, d6 und d8
- 4: d4, d6, d8 und d10
- 5: d4, d6, d8, d10 und d12
- 6: d4, d6, d8, d10, d12 und d20
- 6+: d4, d6, d8, d10, d12 und (Fähigkeitsstufe-5)d20, d.h. für jede weitere Fähigkeitsstufe über 6 wird ein weiterer d20 hinzugefügt.

Ein Würfelergebnis zählt als Erfolg, wenn der Wert kleiner gleich 3 ist. Wenn eine 1 geworfen wird, zählt der Erfolg und der Würfel kann erneut geworfen werden. Dies gilt für alle Würfel mit einer 1 und auch für neue 1en.

Aufgaben erfordern eine bestimmte Anzahl an Erfolgen ja nach Schwierigkeit. Dabei erfordert eine einfache Aufgabe mindestens einen Erfolg, eine mittlere Aufgabe mindestens 2 Erfolge und eine schwere Aufgabe mindestens 3 Erfolge.

Weitere Erfolge zusätzlich zu den benötigten Erfolgen zählen als Bonuserfolge. Bonuserfolge können das Ergebnis positiv beeinflussen.

#### Vor- und Nachteil

Bei einem Wurf kann durch Vor- oder Nachteile der Fähigkeitswert für den Wurf temporär erhöht oder gesenkt werden. Vorteile können beispielsweise durch Ausrüstung, spezielles Wissen/Fähigkeiten oder Charakterhintergrund entstehen. Nachteile entstehen durch Vorteile eines Gegners, Stress oder besondere Umstände. Vor- und Nachteile werden zusammenaddiert, d.h. ein Vorteil gleicht einen Nachteil aus und mehrere Vorteile führen zu einem größeren Vorteil, mehrere Nachteile zu einem größeren Nachteil.

Für jeden Vorteil wird für den Wurf eine um 1 erhöhte Fähigkeitsstufe angenommen, für jeden Nachteil eine um 1 niedrigere. Vor- und Nachteile gleichen sich daher paarweise aus. Durch Vor- bzw. Nachteile kann für einen Wurf eine Fähigkeitsstufe unter 1 erreicht werden. Diese werden wie folgt geworfen:

- 0: d6
- -1: d8
- -2: d10
- -3: d12
- -4: d20
- -5: d100

Ab -5 ist der Wurf immer ein d100.

#### Auf Gut Glück

Ein Charakter kann versuchen, eine Probe, die spezielles Wissen oder Ausbildung (aber keine spezielle Ausrüstung) benötigt, ohne die entsprechende Fähigkeit Auf Gut Glück zu probieren. Dafür wird Wert von -5 angenommen. Entsprechend der Schwierigkeit der Aufgabe kann diese trotzdem mehrere Erfolge benötigen, es ist also mitunter extrem unwahrscheinlich bestimmte Aufgaben Auf Gut Glück zu schaffen.

**Tätigkeiten die spezielle Ausrüstung benötigen können nicht Auf Gut Glück versucht werden.**

::: {.accordion data-title="Beispiele"}
- Fähigkeitsstufe 2:
    - Wurf: d4 und d6
    - Ergebnis des Wurfes: 2,4
    - Ergebnis: 1 Erfolg
- Fähigkeitsstufe 3:
    - Wurf: d4, d6 und d8
    - Ergebnis des Wurfes: 4,2,3
    - Ergebnis: 2 Erfolge
- Fähigkeitsstufe 4 mit Vorteil +1 (insgesamt 5):
    - Wurf: d4, d6, d8, d10 und d12
    - Ergebnis des Wurfes: 3,6,1,2,11
    - Ergebnis des erneuten Wurfes des d8: 3
    - Ergebnis: 3 + 1 Erfolge, insgesamt 4 Erfolge
- Fähigkeitsstufe 1 mit Nachteil -3 (ingesamt -2):
    - Wurf: d10
    - Ergebnis des Wurfes: 4
    - Ergebnis: 0 Erfolge
- Fähigkeitsstufe 6 mit Vorteil +2 (ingesamt 8):
    - Wurf: d4, d6, d8, d10, d12 und 3d20
    - Ergebnis des Wurfes: 4,1,7,10,7,9,2,20
    - Ergebnis des erneuten Wurfes des d6: 3
    - Ergebnis: 2 + 1 Erfolge, insgesamt 3 Erfolge
:::

::: {.accordion data-title="Wahrscheinlichkeiten"}
#### Wahrscheinlichkeit X oder mehr Erfolge zu werfen

<!-- Troll: (count ((accumulate x:= d4 while x = 1) keep {1..3})) -->

Stufe | =0[¹](#wahrscheinlichkeiten-1)      | ≥1       | ≥2       | ≥3       | ≥4       | ≥5       | ≥6      | ≥7      | ≥8      | ≥9
------|----------|----------|----------|----------|----------|----------|---------|---------|---------|---------
-5    |   97,00% |    3,00% |   0,03%  |   0,00%  |   0,00%  |   0,00%  |   0,00% |   0,00% |   0,00% |   0,00%
-4    |   85,00% |   15,00% |   0,75%  |   0,04%  |   0,00%  |   0,00%  |   0,00% |   0,00% |   0,00% |   0,00%
-3    |   75,00% |   25,00% |   2,08%  |   0,17%  |   0,01%  |   0,00%  |   0,00% |   0,00% |   0,00% |   0,00%
-2    |   70,00% |   30,00% |   3,00%  |   0,30%  |   0,03%  |   0,00%  |   0,00% |   0,00% |   0,00% |   0,00%
-1    |   62,50% |   37,50% |   4.69%  |   0,59%  |   0,07%  |   0,01%  |   0,00% |   0,00% |   0,00% |   0,00%
0     |   50,00% |   50,00% |   8,33%  |   1,39%  |   0,23%  |   0,04%  |   0,01% |   0,00% |   0,00% |   0,00%
1     |   25,00% |   75,00% |   18,75% |   4,69%  |   1,17%  |   0,29%  |   0,07% |   0,02% |   0,00% |   0,00%
2     |   12,50% |   87,50% |   48,96% |   16,75% |   4,94%  |   1,36%  |   0,36% |   0,09% |   0,02% |   0,01%
3     |   7,81%  |   92,19% |   64,00% |   30,71% |   11,12% |   3,47%  |   1,00% |   0,27% |   0,07% |   0,02%
4     |   5,47%  |   94,53% |   72,69% |   41,57% |   18,08% |   6,46%  |   2,04% |   0,60% |   0,17% |   0,04%
5     |   4,10%  |   95,90% |   78,26% |   49,81% |   24,64% |   9,91%  |   3,43% |   1,07% |   0,31% |   0,09%
6     |   3,49%  |   96,51% |   80,94% |   54,21% |   28,63% |   12,32% |   4,53% |   1,48% |   0,45% |   0,13%

::: {#wahrscheinlichkeiten-1}
_¹ Wahrscheinlichkeit, keine Erfolge zu werfen_
:::

#### Durchschnittliche Anzahl Erfolge

Stufe | Durchschnitt
------|--------------
-5    | 0,03030
-4    | 0,15789
-3    | 0,27273
-2    | 0,33333
-1    | 0,42857
0     | 0,60000
1     | 1,00000
2     | 1,60000
3     | 2,02857
4     | 2,36190
5     | 2,63463
6     | 2,79253
:::

## Schmerz und Stress

Charaktere besitzen zwei separate Maße, für körperliche Wunden (Schmerz) und geistige Wunden (Stress).

### Schmerz

Wird ein Charakter verwundet wird eine der gegnerischer Erfolge (oder eigenem Fehlschlag) entsprechende Wunde verursacht. Dadurch entsteht Schmerz für den Charakter. Schmerz wird auf 2 unterschiedlichen Skalen eingetragen: Dem Gesamtschmerz und dem Körperteil-Schmerz.

#### Körperteil-Schmerz

Für einen Punkt Körperteil-Schmerz wird ein Kästchen einmal abgestrichen. Es werden erst grüne Kästchen abgestrichen, bevor rote Kästchen abgestrichen werden. Sind alle Kästchen einmal abgestrichen, zählt das Körperteil als verwundet, und beeinträchtigt entsprechende Aktionen. Weitere Treffer streichen bisherige Kästchen ein zweites mal ab, in der gleichen Reihenfolge (grün vor rot). Sind alle Kästchen zweimal abgestrichen, zählt das Körperteil als Zerstört, und muss ersetzt werden. Weitere Treffer erhöhen weder Körperteil noch Gesamtschmerz. Einmal abgestrichene rote Kästchen, sowie alle zweimal abgestrichenen grüne Kästchen zählen als Kritische Wunden.

Sind alle Kästchen von Torso oder Kopf mindestens einmal abgestrichen, verliert der Charakter das Bewusstsein. Sind alle Kästchen von Torso oder Kopf zweimal abgestrichen, ist der Charakter tot.

#### Gesamtschmerz

Gesamtschmerz wird einfach hochgezählt. Übersteigt der Gesamtschmerz eine Schwelle (3\*N), so muss der Charakter eine Zähigkeitsprobe pro überschrittener Schwelle machen, wobei die Schwierigkeit der Probe gleich der Schwellennummer ist (erste Schwelle hat Schwierigkeit 1, zweite Schwelle Schwierigkeit 2, usw.).

::: {.accordion data-title="Beispiel"}
Bob hat im Kampf bereits 4 Schmerz erlitten und eine Zähigkeitsprobe mit Schwierigkeit 1 bestanden. Nun erleidet Bob weitere 5 Schmerz, für einen Gesamtschmerz von 9. Bob muss nun eine Zähigkeitsprobe mit Schwierigkeit 2 bestehen, da 6 = 3\*N → N = 2. Trotz der Tatsache dass Bob bei 9 Schmerz ist, was der nächsten Schwelle entspricht, muss keine weitere Zähigkeitsprobe abgelegt werden, sondern erst wenn diese Schwelle überschritten wird.
:::

### Stress

Stress wird erhöht durch mentale Anstrengungen oder Angriffe, oder durch negative Ereignisse. Übersteigt der Gesamtstress 3\*N, so muss der Charakter eine Willensprobe bestehen oder riskiert einen Zusammenbruch. Willensproben werden äquivalent zu Schmerzproben durchgeführt.

Bei einer gescheiterten Willensprobe erleidet der Charakter einen Zusammenbruch. Der Spieler kann entscheiden, welche Form der Zusammenbruch annimmt:

- **Flucht**: Der Charakter rennt oder kriecht so gut es geht davon, wahlweise schreiend. Der Charakter geht dabei nicht in Deckung.
- **Ohnmacht/Lähmung**: Der Charakter wird bewegungs- und reaktionslos, oder wahlweise ohnmächtig. Der Charakter geht dabei nicht in Deckung.

#### Basisstress

Basisstress ist eine nicht reduzierbare Form von Stress, die durch Cyberware entsteht und als Mindest-Stress funktioniert. Basisstress löst keine Willensproben direkt aus. Wird eine Schwelle durch (Erhöhung von) Basisstress überschritten, wird die Willensprobe erst durchgeführt wenn der Charakter das nächste Mal normalen Stress erhält.

Bestimmte Ausrüstung gibt halben Basisstress (z.B. 0.5 oder 1.5), in diesen Fällen wird aller Basisstress zusammenaddiert und erst am Ende aufgerundet.

## Ruhepausen

Ruhepausen sind Situationen, in denen der Charakter keine Aktivität durchführt und keinem Risiko ausgesetzt ist, sondern sich nur ausruht. Eine _Kurze Ruhepause_ dauert 5-10 Minuten. Eine _Lange Ruhepause_ dauert mindestens eine Stunde. Ruhepausen können nur in Sicherheit durchgeführt werden.

#### Auswirkungen auf Fokus und Stamina

Fokus und Stamina werden in einer Ruhepause wieder komplett aufgefüllt.

#### Auswirkungen auf Schmerz und Stress

Schmerz wird in einer Ruhepausen nur reduziert, sofern der Charakter Medizin verwendet.

In einer _Kurzen Ruhepause_ reduziert sich Stress um so viele Punkte, wie der Charakter in einer Willensprobe an Erfolge erzielt. In einer _Langen Ruhepause_ reduziert sich Stress um so viele Punkte, wie der Charakter Willen besitzt