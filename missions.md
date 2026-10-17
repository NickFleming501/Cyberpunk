# Mission

Wenn Charaktere in ein gegnerisches Gebiet eindringen, wird dies als Mission betrachtet.

<!--
Während Missionen spielt Zeit eine kritische Rolle: Charaktere teilen sich auf um parallel unterschiedliche Ziele zu erreichen während Wachen patrouillieren und Leute langsam verdächtig werden.

## Zeit

Zeit spielt eine kritische Rolle während Mission, besonders wenn sich Teams aufteilen. Je nach Aktion braucht ein Charakter unterschiedlich lange. Die Aktionen werden mit einer Dauer in **Erkundungs-Ticks** bemessen, wobei ein Erkundungs-Tick etwa 1 Minute dauert.

### Erkundungs-Ticks

Aktion    | Erkundungs-Ticks
----------|------------------
Sehr Kurz | 1
Kurz      | 2
Mittel    | 4
Lang      | 8

::: {.accordion data-title="Beispiele"}
Aktion                       | Dauer       | Erkundungs-Ticks
-----------------------------|-------------|------------------
Bewegung                     | Sehr kurz   | 1
Klettern                     | Kurz        | 2
Schleichen                   | Kurz        | 2
Tür aufbrechen               | Kurz        | 2
Raum durchsuchen             | Mittel      | 4
Soziale Interaktion          | Kurz        | 2
Schloss hacken               | Kurz-Mittel | 2-4
Computer hacken              | Mittel      | 4
Informationen sammeln        | Kurz        | 2
Wichtige Daten herunterladen | Lang        | 8
Backdoor installieren        | Kurz        | 2
Verkleidung wecheln          | Kurz        | 2
:::
-->

## Verdacht

Aktionen, oder die Auswirkungen von Aktionen, können bemerkt werden. Dies führt zu wachsendem Verdacht.

Verdacht wird erhöht durch:

- Proben: Das Ergebnis der Probe wird mit der Summe aus Schwierigkeit und Gesamtauffälligkeit (siehe [Auffälligkeit](#auffälligkeit)) verglichen. Bei halben Punkten entscheidet der Erfolg der Probe: Bei Erfolg wird die Schwelle abgerundet, bei einem Fehlschlag wird aufgerundet Ein Verfehlen der Schwelle um 1/2/3/4/5 usw., erhöht den Verdacht um 1/2/3/5/8, selbst wenn die Probe erfolgreich ist.
- Vorkommnisse: Jede weitere Ungewöhnlichkeit erhöht den Verdacht um 1/2/3/4/5

Vorkommnisse können einen Mindestverdacht verursachen:

Vorkommnis             | Minimum | Beispiele
-----------------------|---------|-----------
Regelverstoß           | 5       | Licht wo keins sein sollte, fehlende Person, Lokaler Alarm
Möglicher Eindringling | 15      | Spuren von Hacking/Schlossknacken, fehlende Wache, Alarm
Spuren von Gewalt      | 25      | Aufgebrochene Tür, Waffen, Blutspuren, Schüsse in der Ferne
Bedrohung              | 35      | Tote Person, Bombe, etc.

::: {.accordion data-title="Beispiele für Verdacht durch Proben"}
Probe mit Schwierigkeit 2:

Gesamtauffälligkeit | 1 Erfolg            | 2 Erfolge            | 3 Erfolge
--------------------|---------------------|----------------------|-------------------
0                   | 1 Stufe → 1 Verdacht | gelungen, kein Verdacht | gelungen, kein Verdacht
0,5                 | 2 Stufen → 2 Verdacht | gelungen, kein Verdacht | gelungen, kein Verdacht
1                   | 2 Stufen → 2 Verdacht | gelungen, 1 Stufe → 1 Verdacht | gelungen, kein Verdacht
1,5                 | 3 Stufen → 3 Verdacht | gelungen, 1 Stufe → 1 Verdacht | gelungen, kein Verdacht
2                   | 3 Stufen → 3 Verdacht | gelungen, 2 Stufen → 2 Verdacht | gelungen, 1 Stufe → 1 Verdacht
:::

### Verdachtsstufen

Je größer der Verdacht, um so aktiver werden Wachen:

Stufe         | Bereich | Wachen                              | Kommunikation mit anderen Wachen | Bei Sichtkontakt
--------------|---------|-------------------------------------|----------------------------------|------------------
Routine       | 0-4     | Normale Patrouillen                 | Keine Kommunikation              | Beobachtet nur
Aufmerksam    | 5-14    | Untersuchen Verdacht                | Teilt Verdacht in der Nähe       | Fragt nach ID
Misstrauisch  | 15-24   | Checkpoints, Angepasste Patrouillen | Teilt Verdacht im Gebiet         | Fragt nach ID und verifiziert
Alarmiert     | 25-34   | Partieller Lockdown, Durchsuchung   | Teilt Verdacht mit allen Wachen  | Nimmt in Gewahrsam
Einsatzbereit | 35-49   | Kompletter Lockdown                 | Teilt Verdacht mit Autorität     | Fordert Verstärkung an
Kampfbereit   | 50+     | Externe Verstärkung                 | -                                | Eröffnet Feuer
