---
layout: post
title: "„Kontext, bitte!“ – warum KI-Governance ohne Kontext scheitert"
date: 2026-01-29
last_modified_at: 2026-01-29
categories: [Standards, Risiko-Management]
excerpt: "Warum Kontext der blinde Fleck vieler KI-Governance-Ansätze ist – und wie Standards wie ISO/IEC 42001, ISO/IEC 42005 und Value-based Engineering helfen, ihn systematisch zu adressieren."
---

Fairness. Transparenz. Vertrauen.

Diese Begriffe tauchen in vielen Beiträgen zu KI-Governance auf. Und
ja – sie sind wichtig.

Das Problem: Ohne Kontext bleiben sie leer.

Wer nicht versteht, _wo_, für _wen_ und _unter welchen Bedingungen_
ein KI-System eingesetzt wird, wird diese Begriffe nie sinnvoll mit
Inhalt füllen können. 

Wie nähert man sich also der Frage an, was diese Begriffe eigentlich
bedeuten sollen?

Es ist eigentlich recht simpel: Auf den Kontext kommt es
an. Vielleicht erscheint das fast trivial - aber zumindest auf den
zweiten Blick ist es das nicht. Denn den Kontext eines IT-Systems zu
verstehen ist alles andere als simpel.

Dennoch wird wenig über den Kontext gesprochen. Zu Unrecht. In diesem
Blogpost möchte ich kurz ein paar Gedanken und Anknüpfungspunkte
zusammenfassen.

## Die Relevanz des Kontextes verstehen
In der Entwicklung von IT-Systemen arbeiten wir häufig mit dem Kontext
eines IT-Systems. Beispielsweise wenn wir uns über die Bedürfnisse
unserer Nutzer:innen Gedanken machen. 

Wer wie ich in einer Zeit studiert hat, in der sich UML höchster
Beliebtheit erfreute, der kennt vielleicht
"Kontext-Diagramme". Strichmännchen mit Ellipsen, die User und Use
Cases darstellen sollen.

Tatsächlich ist dies aber nur ein kleiner Ausschnitt des tatsächlichen
Kontexts. Denn ein System hat nicht nur Strichmännchen-User und Use
Cases. Es hat vielleicht ganz verschiedene Arten von Nutzer:innen,
z.B. Ärzt:innen und Patient:innen im medizinischen Kontext. Es hat
einen Einsatzort in  der 'echten Welt', vielleicht nur eine Stadt,
vielleicht ein Land, vielleicht viele oder gar alle Länder der Welt. 

Ein gutes Verständnis dieses Kontexts war sicherlich schon immer
relevant, um gute Software-Systeme zu bauen - das ist etwa die Aufgabe
des Product Owners in Scrum. 

Bei der KI ist der Kontext aber noch viel kritischer, wie ein paar
einfache Beispiele verdeutlichen:
* Trainingsdaten müssen repräsentativ im Einsatz-Kontext des geplanten
  Systems sein.
* Gesetzliche Anforderungen weichen international stark nach
  Einsatzland ab.
* Das Werteverständnis, wenn es etwa um Fairness geht, ist nicht
  einheitlich. Unterschiedliche Kulturen setzen verschiedene Maßstäbe
  an.
  
Der letzte Punkt ist auch vor dem Hintergrund relevant, dass mögliche
Reputationsschäden als eines der Top-Risiken beim Einsatz von KI gesehen
wird.

Kurzum: Der Kontext eines KI-Systems verdient wesentlich mehr
Aufmerksamkeit, als wir ihm bisher geben.

## Der Kontext in ISO 42001 und ISO 42005 
Die [ISO/IEC
  42001](/standards/2025/08/20/kurz-erklaert-iso-iec-42001-2023.html)
  widmet dem Kontext der Organisation das Kapitel 4 und folgt damit
  der Logik von ISO-Managementsystemen.
  
Dabei wird grob in interne und externe Faktoren unterschieden.
*  Externe Faktoren beinhalten etwa rechtliche Rahmenbedingungen und
   kulturelle Aspekte.
*  Interne Faktoren betrachten Eigenschaften und Ziele der
   Organisation, also etwa bestehende vertragliche Rahmenbedingungen,
   Ziele und bestehende Richtlinien.

Hier taucht der Kontext also sehr prominent auf - jedoch nicht auf
Ebene des einzelnen KI-Systems. Dennoch findet sich ein interessanter
Verweis an dieser Stelle: Die Begriffsnorm [ISO/IEC
22989](https://www.iso.org/standard/74296.html) listet
unterschiedliche _AI stakeholder roles_ auf (Abschnitt 5.19), die für
die Betrachtung relevant sind.

Mehr Informationen dazu, was der Kontext beinhaltet, sind in der
ergänzenden Norm [ISO/IEC
42005](/standards/2025/09/30/kurz-erklaert-iso-iec-42005-2025.html)
(z.B. Abschnitt 5.3) aufgelistet. Hierzu zählen System-Beschreibung,
Features und Zweck. Details dazu, wie dieser Kontext modelliert werden
kann, bleibt die Norm allerdings ebenfalls schuldig.

## Der Kontext von Stakeholder:innen
Bei all den (in der Sache richtigen) Ausführungen zum Kontext kommt
ein Aspekt leider zu kurz: Die Rolle von Stakeholder:innen. Laut dem
[AI Index
Report](https://hai.stanford.edu/ai-index/2025-ai-index-report) zählen
Risiken wie Reputationsschäden, Erklärbarkeit, sowie Teilhabe und
Fairness zu den Top 10 beim Einsatz von KI und werden jeweils von mehr
als einem Drittel der befragten Organisationen als relevant
eingeschätzt. Diese Risiken sind insbesondere mit den Erwartungen der
Menschen verbunden, die mit dem System in Berührung kommen - also mit
den Stakeholder:innen.

Wie also kann man diese Erwartungen proaktiv ermitteln und somit das
Risiko minimieren, nach Veröffentlichung einer Anwendung mit negativen
Rückmeldungen konfrontiert zu werden?

Wie ausgeführt muss man den Kontext modellieren, um Risiken zu
verstehen. Stakeholder:innen haben einen eigenen Kontext in ihrer
Lebenssituation. Dieser ist für Außenstehende nur schwer
nachvollziehbar. Ein Beispiel, das ich oft nutze, ist das von Menschen
mit mangelnden Sprachkenntnissen. Als Deutscher kann ich mir durchaus
vorstellen, dass es schwierig ist, sich im Alltag ohne solche
Sprachkenntnisse hier in München zurechtzufinden. Allerdings ist
Deutsch meine Muttersprache – ich verstehe das Problem grundsätzlich,
wie es sich konkret äußert, welche Situationen besonders kompliziert
sind, etc. kann ich mir aber nur bedingt vorstellen.

Um diesen Stakeholder-Kontext sinnvoll zu ermitteln muss man also viel
mehr über die Stakeholder:innen herausfinden. An diesem Punkt greifen
ISO 42001 und ISO 42005 aus meiner Perspektive viel zu kurz. Man
könnte soweit gehen zu sagen: Beide Standards stellen hier einen ganz
wesentlichen Erfolgsfaktor von KI-Produkten (und eine Quelle großer
Risiken) stark verkürzt dar. 

Um hier konkreter zu werden, muss man also andere Werkzeuge
nutzen. Ein ISO-Standard, der an dieser Stelle hilfreich ist, ist die
[ISO 5339](https://www.iso.org/standard/81120.html). Dieser Standard
stellt ein Framework zur Verfügung, mit dem Stakeholder:innen
systematisch erfasst werden können. Zudem beinhaltet ISO 5339 einen
Fragenkatalog pro Stakeholder, der dabei helfen soll, relevante
Aspekte der jeweiligen Perspektive besser zu verstehen.

## Der Kontext in Value-based Engineering (VBE)
Der VBE-Prozess, basierend auf [ISO/IEC/IEEE
24748-7000](https://www.iso.org/standard/84893.html), kennt die drei Phasen
* "Konzeption und Kontextanalyse",
* "Werteerkundung und Priorisierung" und
* "Ethisches IT-Systemdesign".

Die erste Phase widmet sich also ausführlich der Frage der
Kontextbeschreibung und Analyse, wobei insbesondere das zu
entwickelnde System (_System-of-Interest_, SOI), der Systemverbund
(_System-of-Systems_, SOS) und die dazugehörigen Partner beschrieben
werden. Diese Phase erklärt im Detail, was in den ISO-Normen 42001 und
42005 eher oberflächlich dargestellt wird: Was ist das betrachtete
System, was sind die Ziele und was sind die bekannten
Rahmenbedingungen. Die Tiefe der Beschreibung wird abhängig vom
Fortschritt eines Projektes zwar abweichen, allerdings kann auch ein
früher "Snapshot" eine gute Grundlage für ein besseres
Kontextverständnis sein.

Der Kontext der Stakeholder:innen wird nun in der zweiten Phase
genauer untersucht: Eine initiale Top-Down-Analyse (_Conceptual
Analysis_) wird optimalerweise von einer geschulten Person
durchgeführt. Der Standard spricht hier vom sogenannten _Value Lead_.

Stakeholder:innen werden dann im nächsten Schritt mit einbezogen
(Bottom-up). Sie vertreten bestimmte Gruppen von Personen, die vom
System direkt oder indirekt betroffen sind. Manche vertreten "sich
selbst", da sie Teil einer bestimmten Gruppe sind (z.B. Kinder beim
Design von kinderfreundlichen Anwendungen, wie dies etwa [IEEE
2089](https://standards.ieee.org/ieee/2089/7633/) vorsieht). In
anderen Fällen können auch gewählte Vertreter:innen, wie etwa von
Gewerkschaften, oder auch NGOs mit einbezogen
werden. Nichtregierungsorganisationen sind auch dann relevant, wenn
Stakeholder nicht für sich selbst sprechen können. Dies wäre etwa der
Fall, wenn es um Schützenswertes wie das Tierwohl oder die Umwelt
geht. Man sieht: Durch die Erweiterung des Begriffs der
Stakeholder:innen können auch weitere, wichtige Aspekte in die
Modellierung mit einbezogen werden.

An diesem Punkt ist auch der Aufwand gut mit dem Risiko einer
Anwendung skalierbar. Für neue Anwendungen kann ein Workshop das
richtige Format sein (wie ihn etwa die [Stadt
Wien](https://digitales.wien.gv.at/workshop-value-based-engineering/)
abgehalten hat). In anderen Fällen mag auch ein schlankes Format, wie
etwa Experten-Interviews, eine gute Lösung sein. In beiden Fällen wird
jedoch die gleiche Struktur verwendet. Dies macht den Prozess
nachvollziehbar und wiederholbar. Zusätzlich beantwortet VBE die
Frage, wie man so gefundene Risiken nun in konkrete, umsetzbare
Anforderungen übersetzt.

## Zusammengefasst
Das Verständnis des System-Kontextes ist entscheidend dafür, Risiken
zu adressieren und ein "gutes" IT-System zu entwerfen. Dies ist bei KI
noch wesentlich wichtiger als in der klassischen Software, denn große
Risikoblöcke wie Reputation, Fairness und mehr hängen vom Kontext und
letztlich den Präferenzen, Sorgen und Nöten von Stakeholder:innen ab.

Stakeholder:innen und den von ihnen repräsentierten Kontext zu
verstehen ist deshalb immens wichtig. Dies sticht in Standards wie ISO
42001 und ISO 42005 nur bedingt heraus. ISO 5339 ist hier eine gute
Ergänzung um die Stakeholder:innen besser zu verstehen.

*Wer KI-Governance und Risikominimierung ernst nimmt, kommt also an
einer systematischen Kontext- und Stakeholder-Analyse nicht
vorbei*. Genau hier setzt VBE an und räumt der Modellierung des
Kontexts, sowie der Einbindung von Stakeholder:innen entsprechend Raum
ein.
