# tcvfbgoeswet
Ein sicherlich passender Anglizismus jedoch von der Sexualisierungsbeauftragen zu prüfender Projektname für das Vorhaben:
## Modernisierung und Deregulierung der Automatisierung der Platzberegenungsanalge des T.C. VfB Kirchhellen e.V.

#### Hintergrund
Seit der Finalisierung der Umbau und Sanierungsmaßnahmen im März 2007 bei der drei Plätze westllich der  Teilungslinie auf die östliche Seite der Anlage und ein 4. Platz komplett saniert wurden (siehe https://www.tc-vfb-kirchhellen.de/geschichte) , verfügt die Anlage über eine automatisierte Sprenkleranlage, welche durch einen Bedienkasten links vom Platz 1 gesteuert wird. Der Bedienkasten der Zugang auf das SPS-artige Bedienfeld gewährt ist im Regelfall abgeschlossen. Jediglich 2-4 Mitglieder verfügen über einen Schlüssel zur Öffnung des Bedienkasten. Im wesentlichen kann die Anlage manuell oder automatisiert beregnet werden. Bei der manuellen Steuerung wird das Bewässern entweder eines Platzes oder eines Zyklus, sprich alle 8 Plätze werden nacheinander bewässert gestartet. Der automatisiwerte Modus zeichnet sich dadurch aus, dass Zyklen der Beregnung aller Plätze zu festgelegten Zeiten gestartet werden. Aktuell abendds gegen 21:00 h jeweils 10 Minuten und morgens gegen 6:00 ebenenfalls für 10 Minuten.

Auf den Plätzen befinden sich 4 Düsen aus denen die Bewässerung der Anlage erfolgt. Die Erfahrung hat gelehrt, dass diese Düsen recht waartungsintensiv sind. Hierbei werden sowohl Richtung der Beregnung eingestellt als auch Verschleissteile durch engagierte Mitglieder im wesentlichen aus den Herren 70 Hans-Willi Grusemann und Peter Imberg sowie dem aktuellen Geschäftsführer Hardy Waegemann geleistet. 

Im Juni 2025 ist während eines wohlverdienten Urlaubs des Geschäftsführers bei gleihzeitiger Durchführung on Medenspielen und sehr, sehr waremn Wetters (eigentlich waren alle Spiele vom Bezirk abgesagt, die ganze Problematik der Beregnungssituation offenbar geworden, da auf einmal kein Schlüssel für den Beregnungskasten zur Verfügung stand. 

### Verbesserungspotential
1. Die manuelle Bewässerung der Plätze sollte direkt von Mitgliedern vom Platz aus gestartet werden können.
2. Die Regelung der Zugangsbeschränkung via mechanischem Schlüssel ist altbacken und sollte durch modernere weniger exklusive und elektronsiche Verfahren gesteuert werden
3. Gleichzeitig ist dabei aber zu berücksichtigen, dass auf einzelnen Plätzen die Beregnungsanlage temporär eingeschränkt ist, da die Düsen gewartet werden müssen.

### Grobkonzept
Die SPS-artige Steuerung der Anlage wird durch eine benutzerfreundliche Steuerung mittlels Touchpad und mobiler Anwendung (App) ersetzt. Zusätzlich / alternativ kann darüber nachgedacht werden, smarte Schalter an den einzelnen Plätzen einzurichten, mit der die manuelle Beregnung eines einzelnen Platzes gestartet werden kann. Smarte Schalter haben hierbei den Vorteil, dass Sie z.B. nachts deaktiviert werden können, so dass Vandalisumus vorgebeugt werden kann. 

Als Steuerungsgeräte bieten sich Rasberry Pies an. Rasberries sind sehr preiswerte Mincomputer, die mittels des offenen und damit Lizenzkostenlosen Betriebssystems Linux betrieben werden. Die Kommunikation der Steuerungselemente erfolgt über WLAN. Damit die Anlage über App gesteuert werden kann, ist es erforderlich, dass Internetzugang z.B mittels einer preiswerten SIM Karte hergestellt wird. 

Auf tiefer Ebene erfolgt die Steuerung der Anlage wie folgt: Im Endeffekt müssen Steuerungsleitungen der Anlage mit Strom versorgt werden. Dies ist, wenn man so will die "Ausgabe" der SPS-Steuerungsanlage. Dieser Strom steuert Öfffnung der Düsen und Start der Pumpe zur Bereeglung, welche wiederumg die Zufuhr von Wasser auf die Plätze als Ausgabe haben.
Dieser Ansatz der Steuerung auf recht tiefer Ebene hat den Vorteil, dass sowohl die SPS-Steuerung der Anlage, als auch die Smarte Beregnung via TCVFB Goes Wet parallel betrieben werden können, was die allgemeine Akzeptanz bei den Mitgliedern als auch einen Parallelbetrieb und stufenweise Erweiterung der Lösung ermöglicht.






Das Tochhpad wird in der Hütte am Center





