# Einleitung
Ein plastischer, durch einen Anglizismus beschriebener Projektname für das Vorhaben der
## Modernisierung und Demokratisierung der Automatisierung der Platzberegenungsanalge des T.C. VfB Kirchhellen e.V.

###Ausgangslage
Die Sportanlage des T.C. VfB Kirchhellen e.V verfügt seit dem Jahr 2007 über eine automatisierte Sprenkleranlage mit der die Plätze bewässert werden können. Auf jedem der 8 Plätze sind hierzu X Sprenklerdüsen, ähnlich eines Rasensprenklers im Boden installiert, die individuell von Servicetechnikern hinsichtlich des zu beregnetem Kreisausschnitt mit der beiden Parameter horizontaler und vertikaler Winkel der Beregnung eingestellt werden können. Aufgabe der Servicetechniker ist es, diese Parameter so einzustellen, das eine möglichst gleichmäßige Bewässerung des Platzes gewährleistet ist. Hierbei ist zu berücksichtigen, dass sich durch die Düsen bestrahlte Kreissektoren einerseits überschneidn können, anderseits aber auch Flächen existieren, welche nur von einer Düse aus beregnet werden können. Desweiteren haben die Servicetechniker zu berücksichtigen, dass bestimmte Platzbereiche durch Grundwasserspiegelsituation, eventuell sogar durch Bergschädeninhärent feuchter/trocker sind als andere. Wenn man zudem noch in Betracht zieht, dass auf den einzelnen Plätzen unterschiedliche Windverhältnisse herrschen und das einzelne Düsen unter Umständen defekt sein können, wird deutlich, dass das Einstellen der Düsen alles andere als eine triviale Aufgabe ist, die deshalb auch nicht Gegenstand des Projektauftrages sein wird. In IT-Sprache übersetzt "Hardware-mäßige Einstellung der beregneten Kreisausschnitte auf jedem einzuelnen Platz ist out-of scope !
Neben der automatischen Beregnung können und werden die Plätze manuell bewässert mittels zweier auf jedem Platz angebrachten Schläuche mit Spritzdüse ähnlich der eines Feuerwehrschlauches bewässert. Das Ein- und Ausschalten der Beregnung erfolgt dadurch, dass einerseits ein Wasserhahn, welcher sich in der Mitte des Platzes zu öffnen bzw. zu schließen ist, reguliert. Anschließend wird ein Hebel der Komponente (Bauteil) der Spritzeam am anderen Ende des Schlauches, ist vom "Beregner" geöffnet bzw. geschlossen. Der Beregner hat nun selbständig für die gleichmäßige und  adäquate Bewässerung (bei Trockenheit wird mehr Wasser als bei feuchtem Wetter benötigt) zu sorgen. Hierzu geht der Beregner über den Platz, past Höh   


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





