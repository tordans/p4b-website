+++
author = ""
categories = []
date = ""
description = ""
draft = true
image = ""
summary = ""
thumbnail = ""
title = "WALKIE Projekt erfolgreich beendet "
translationKey = ""

+++
## Neue Features von GOAT: Walkability Index und Fußgängerpotenzialströme

Zu Fuß gehen ist die wohl nachhaltigste Form der Mobilität, denn es ist ökologisch, sozial, ökonomisch und basiert somit auf allen drei Säulen der Nachhaltigkeit. Dafür ist eine sichere und komfortable Fußgängerinfrastruktur notwendig - und zur Verbesserung dieser haben wir einen Walkability Index entwickelt. 

Im Rahmen des Projektes [WALKIE](https://plan4better.de/posts/2021-04-06-walkability-index/) („WALKability IndEx“) haben wir eine dreimonatige Förderung durch das [Verkehrsministerium Baden-Württemberg](https://vm.baden-wuerttemberg.de/de/startseite/) im Rahmen der Anschlussförderung des [MobiDataBW Hackathons 2020](https://vm.baden-wuerttemberg.de/de/politik-zukunft/zukunftskonzepte/digitale-mobilitaet/mobidata-bw-hackathon/) erhalten. Diese ermöglichte uns den Index in enger Zusammenarbeit mit der Pilotkommune [Freiburg](https://digital.freiburg.de/) zu konkretisieren und im Anschluss erfolgreich auf diese zu übertragen. 

Somit haben wir sowohl alle angegebenen Meilensteine als auch das Hauptziel erreicht! GOAT wurde auf eine neue Stadt übertragen und konnte um neue Features erweitert werden, welche sowohl die aktuelle Fußgängerfreundlichkeit (engl. Walkability) der Städte, als auch Verbesserungspotenziale, priorisiert darstellen können.

## Konkretisierung des Walkability-Index:

Das digitale Webtool GOAT war zuvor bereits in der Lage, die Verfügbarkeit von Gehwegen darzustellen. Mit der Einbindung des Walkability Indexes wird nun auch die Attraktivität für Fußgänger berücksichtigt. 

Die Idee zur Entwicklung von WALKIE sowie ein erster Prototyp entstanden im Rahmen des MobiDataBW Hackathons im November 2020. Das Team nutzte die darauffolgende Innovationsphase (März-Juni 2021) zur Weiterentwicklung und Verstetigung der Funktionen, mit der Stadt Freiburg als Pilotstandort. WALKIE ist nun ein aussagekräftiger, multi-kriterieller Walkability Index, der die Attraktivität des Zufußgehens quantitativ abbildet.

Zunächst wurden auf Basis bestehender wissenschaftlicher Erkenntnisse die Qualitätskriterien der Walkability sowie deren Gewichtungen ermittelt. Als Resultat wurde der Walkability Index mit sechs Kategorien, die in 22 Sub-Indikatoren unterteilt sind, entwickelt.

Die Walkability-Kategorien:

* Gehkomfort
* Schutz vor dem Straßenverkehr
* Beleuchtung & subjektive Sicherheit
* Belebtheit & Gehumgebung
* Vegetation & Gewässer
* Urbane Ausstattung

Die zahlreichen Einzelindikatoren wurden in einem Algorithmus bewertet, gewichtet und zu einem Gesamt-Walkability-Score aggregiert. Dabei wurden Scores zwischen 0 und 100 errechnet, wobei 0 eine niedrige und 100 eine hohe Fußgängerfreundlichkeit bedeuten.

Wir haben unterschiedliche Datenquellen benutzt. Zum einen durch Crowdsorcing erhobene Datensätze, aber auch die OpenData-Plattformen von Stadt und Land (z.B. [FreiGIS](https://geoportal.freiburg.de/freigis/)). Darüber hinaus haben wir für die Stadt Freiburg über 10.000 Bildaufnahmen des Straßenraums über die Plattform [Mapillary](https://www.mapillary.com/) erhoben. 

Daraus konnten wir u.a. Infos zu den verschiedenen Attributen der Straßen oder zum Vorhandensein von Straßenlaternen, Parkbänken, etc. herauslesen. Besonders innovativ war dabei die Nutzung der Mapillary-API: automatisierte KI-Algorithmen erkennen und lesen die Objekte aus den Bildsequenzen aus. In [diesem Blogartikel](https://plan4better.de/de/posts/2021-15-06-high-quality-data-now-automatic/ "Automatisierte Bilderkennung") erklären wir genauer, wie wir Mapillary für die automatisierte Objekterkennung für die einzelnen Wegabschnitte in Freiburg genutzt haben.

_Bild_

Die enge und konstruktive Zusammenarbeit mit der Pilotstadt Freiburg war erheblich für die Entwicklung von WALKIE und den erfolgreichen Projektverlauf. Dazu hat sich das Team mehrmals mit Vertretenden der Einheit DIGIT (Digitales und IT) der Stadt Freiburg getroffen und ihr Feedback in den Entwicklungsprozess von WALKIE eingebunden. Außerdem wurden die lokal verfügbaren Daten in GOAT eingebunden und eine [auf die Stadt Freiburg abgestimmte GOAT-Version](https://freiburg.open-accessibility.org/) entwickelt.

In dieser GOAT-Version wurde auch der Walkability Index erstmals veröffentlicht. Somit kann pro Wegabschnitt in Freiburg die Walkability dargestellt werden. Die grünen Wege haben einen hohen Score, d.h. sie sind besonders fußgängerfreundlich. Bei orangenen Wegen ist ein niedriger Walkability Score berechnet und es besteht somit Verbesserungspotenzial. So können Schwachstellen sehr gut und verständlich visualisiert werden.

_Bild_

## Fußgängerpotenzialströme – Welche Straßen sind hoch frequentiert?

Die Frequentierung der Straßen ist für die Priorisierung der Verbesserungsmaßnahmen ebenfalls ein wichtiger Anhaltspunkt. Dafür wurde ein weiterer Indikator entwickelt, der die Fußgängerpotenzialströme aufzeigt.

Als Anwendungsbeispiel wurden für die Stadt Freiburg Fußgängerpotenzialströme für Schulwege zu Grundschulen gewählt. Der Anteil an Kindern zwischen 6 und 9 Jahren war bekannt, dadurch konnte pro Wohnhaus abgeschätzt werden, wie viele Kinder in diesem wohnen. Im nächsten Schritt wurde von allen Wohnhäusern aus der kürzeste Weg zur jeweiligen Bezirksgrundschule berechnet. Die einzelnen Ströme wurden aufsummiert und ergeben die aggregierten Fußgängerpotenzialströme.

Dies wird durch die Dicke der Linie visualisiert – diese zeigt auf, wie viele Kinder potenziell diesen Weg gehen.

_Bild_

Werden die zwei Layer gegenübergestellt, kann die Frage beantwortet werden, welche Wege eine hohe Frequentierung und zeitgleich eine geringe Walkability haben. Diese sollten bei der Planung priorisiert werden.

Die hier beispielhaft dargestellte Walkability für den Schulweg kann auf weitere Untersuchungsgebiete übertragen werden. Die Planer*innen der Stadt Freiburg haben im Rahmen des Projektes in einem Workshop GOAT mit den neuen Indikatoren getestet und als nützlich und positiv bewertet. Mit Projektende steht GOAT für weitere 3 Monate offen für Freiburg zur Verfügung. 

[Hier ](https://freiburg.open-accessibility.org/ "GOAT Version Freiburg")können Sie selbst einen Blick auf die entwickelte GOAT-Version werfen und die neuen Features für das Untersuchungsgebiet Freiburg ausprobieren!

## Wie geht es weiter?

Das Team steht derzeit weiterhin mit dem DIGIT Freiburg im Kontakt, um - über das WALKIE Projekt hinaus - mögliche Einsatzfelder von GOAT zu untersuchen und die Anforderungen an das Tool zu definieren.![](/images/hackathon.jpg)