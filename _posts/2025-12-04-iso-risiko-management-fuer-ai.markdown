---
layout: post
title: "ISO-basiertes Risiko-Management für KI: Der Dreiklang von ISO 42001, 31000 und 23894"
date: 2025-12-04
last_modified_at: 2025-12-04
categories: [Standards, Risiko-Management]
tags: [ISO 42001, ISO 23894]
excerpt: "Eine kurze Einführung in das Risiko-Management für KI laut ISO/IEC 23498 und die Verbindung zu ISO/IEC 42001."
---

ISO-Standards zu lesen hat mich schon das ein oder andere Mal
frustriert: Scheinbar verweist ein Standard auf den nächsten und, wie
es so ist, hat man gefühlt auch nie alle Standards lizenzensiert im
Zugriff. Pure Boshaftigkeit? Könnte man annehmen, aber es ist, denke
ich, nicht der Fall. Vielmehr muss man die ISO-Standards als eine Art
Netzwerk sehen - manche Standards stehen nebeneinander und nutzen die
gleiche Struktur für unterschiedliche Aspekte (z.B. ISO 27001 und ISO
42001). Manche Standards sind Spezialisierungen, die allgemeine
Prinzipien für bestimmte Anwendungsfälle konkretisieren.

## Komponenten eines ISO-basierten KI-Risiko-Managements
Als eine solche Spezialisierung kann man das ISO-Risiko-Management für
KI sehen, das ich heute etwas näher erläutern möchte:
* Wie wir in unserem [Artikel zu **ISO/IEC
  42001**](/standards/2025/08/20/kurz-erklaert-iso-iec-42001-2023.html)
  gesehen haben, beschreibt dieser Standard sowohl Elemente eines
  KI-Management-Systems, als auch die Abläufe (*Plan-Do-Check-Act*,
  kurz *PDCA*). Ein Teil der notwendigen Arbeitsschritte: Das
  Aufsetzen eines Risiko-Managements.
* Hier kommt der Standard **[ISO/IEC
23894](https://www.iso.org/standard/77304.html)**, *Information
technology — Artificial intelligence — Guidance on risk management*,
ins Spiel.
* Dieser wiederum ist eine Konkretisierung des Standards **[ISO
  31000](https://www.iso.org/standard/65694.html)**, *Risk management -
  Guidelines*, also der allgemeinen Richtlinien zum Managen von
  Risiken, wie sie in der großen Teilen der ISO-Welt zum Einsatz
  kommen.


{% include figure.html
preview="/assets/images/iso-23894-einordnung-klein.png"
full="/assets/images/iso-23894-einordnung.png" alt="Einordung ISO
23894" caption="Abbildung: Einordnung von ISO/IEC 42005 – zum Vergrößern
klicken" %}

Kurz gefasst ergibt sich folgendes Bild:
* ISO 42001 verlangt nach Management von KI-Risiken.
* ISO 31000 beschreibt den allgemeinen Rahmen für das
  Management jeglicher Risiken. Risiken werden dabei als Effekte von
  Unsicherheit definiert, die positiv oder negativ sein können.
* ISO 23894 detailliert, was bei KI-Risiken speziell ist.

Um nun zu verstehen, wie das funktioniert, beginnen wir am besten bei
ISO 31000.

## Das Framework für Risiko-Management: ISO 31000
Ein Blick in das öffentlich zugängliche [Kapitel zum
Scope](https://www.iso.org/obp/ui/en/#iso:std:iso:31000:ed-2:v1:en)
der ISO 31001 genügt, um **die drei wesentlichen Bestandteile** dieses
Risiko-Management-Ansatzes kennenzulernen:
1. Prinzipien,
2. ein Framework für die Integration des Risiko-Managements in die
eigene Organisation und
3. der Risiko-Management-Prozess im engeren Sinne.

Bei den **Prinzipien** handelt es sich um wichtige Leitgedanken eines
effektiven Risiko-Managements. Das Prinzip *Dynamic* bezieht sich etwa
darauf, dass das Risiko-Management eine Organisation mit sich
verändernden Rahmenbedingungen (und damit auch sich ändernden Risiken)
umgehen muss.

Das **Framework** beschreibt die Integration des Risiko-Managements im
weiteren Sinne. Risiko-Management zu integrieren ist kein "One-Shot",
sondern vielmehr ein iterativer Prozess. Die Notwendigkeit, das
Vorgehen anzupassen ergibt sich schon alleine aus der Tatsache, dass
auch das Umfeld einer Organisation nicht statisch ist. Hinzu kommen
natürlich auch Erkenntnisse aus der Praxis, die es zu berücksichtigen
gilt.

Wer hier nun aufgepasst hat sieht auch schon, dass diese Gedankengänge
sich auch in der ISO 42001 widerspiegeln. Den Gedanken des
integrierten Risiko-Managements sieht man etwa an der Zuteilung von
Rollen (ISO 42001, Kapitel 5.3). Das iterative Vorgehen ist zuletzt in
der *PDCA*-Logik der ISO 42001 abgebildet.

Der **Risiko-Management-Prozess** als dritte Komponente beschreibt
dann genauer das Vorgehen in der Praxis, von **Identifikation, Analyse
und Bewertung bis hin zur Behandlung des Risikos**. Ein Blick lohnt
sich in diesem Kontext auch in die Definitionen, die neben dem
Risiko-Begriff selbst auch andere wichtige Konzepte beinhalten, etwa
das Konzept des *Risk Appetites* einer Organisation, also dem Willen,
Risiken auf sich zu nehmen. Die Definitionen in der ISO 31000 fallen
etwas kurz aus. Einen ausführlichen Überblick über alle relevanten
Begriffe - Hilfe naht mit [ISO
31073](https://www.iso.org/standard/79637.html). Dieser
Definitionsstandard ist auch größtenteils kostenlos einsehbar.

Jeder Schritt des Prozesses wird erläutert. Viele Details und
Templates bleiben im Standard (wie so oft) nicht detailliert
ausgeführt. Allerdings existiert einiges an hilfreicher Literatur zu
den Methoden (wie etwas [Risikomanagement von
F. Romeike](https://link.springer.com/book/10.1007/978-3-658-13952-0),
sowie viele Ratgeber für Sektoren spezifisches Risiko-Management.

Am Ende, und das kann man als Stärke, wie Schwäche sehen, versucht die
ISO mit diesem Standard 'den ganz großen Rahmen' zu spannen.

## Risiko-Management für KI mit ISO 23894
Wenn wir also die Struktur und Intention der ISO 31000 verstanden haben, stellt sich die Frage: Wie passt KI da hinein?

Diese Lücke versucht nun ISO 23894 zu füllen. Wie macht der Standard
das? Nun, eigentlich kann man ihn fast ein bisschen wie ein *Add-On*
zu ISO 31000 begreifen: Die drei Komponenten der ISO 31000,
Prinzipien, Framework und Prozess, werden fast schon kommentarartig
ergänzt um Aspekte, die im Kontext der KI besonders wichtig sind. 

Das oben genannte Prinzip *Dynamic* wird so etwa im Kontext der KI
nochmals genauer ausdetailliert. Denn, darauf weist ISO 23894,
KI-Systeme sind selbst besonders dynamisch durch kontinuierliches
Training oder aber auch das dynamische Umfeld (z.B. auf die
[Gesetzgebung](https://www.politico.eu/article/gpai-code-of-practice-to-come-in-weeks-ai-office-says/)
bezogen), in dem Sie eingesetzt werden.

Dieses einfache Beispiel illustriert die Funktion von ISO 23894 als
eine Sammlung von Ergänzungen und Hinweisen zu jedem einzelnen Punkt
des allgemeinen Frameworks nach ISO 31000. Einige der aufgeworfenen
Themen, wie etwa die dynamische Natur von KI als Technologie, werden
KI-Experten nicht überraschen. Insofern sollte man ISO 23894 auf zwei
Ebenen als Hilfestellung sehen:
* Wer sich mit Risiko-Management auskennt, aber noch wenig Erfahrung
  mit KI hat, erhält viele Hinweise zu möglichen Knackpunkten, die
  sich aus der Technologie ergeben.
* Wer sich sowohl mit Risiko-Management, als auch mit KI auskennt,
  der lernt vielleicht nichts grundsätzlich neues - allerdings kann
  ISO 23894 dann immer noch als eine gute, standardisierte Checkliste
  mit wichtigen Aspekten im KI-Risiko-Management dienen.

## Risiko-Management in der ISO 42001
Das Roll-Out eines KI-Management-Systems nach ISO 42001 kann man in
sich selbst als eine Maßnahme der Risiko-Behandlung sehen: Es
beinhaltet die Abläufe und die organisatorischen Elemente, die
notwendig sind, um KI (und die sich aus ihr ergebenden Risiken) zu
managen. Das umfasst sowohl die Etablierung des Systems selbst (was
dem Framework-Gedanken entspricht), als auch die Durchführung des
konkreten Risiko-Managements – jeweils geleitet von übergeordneten
Prinzipien.

Der Prozess, Risiken zu identifizieren, zu analysieren, zu bewerten und
zu behandeln (z.B. durch die Etablierung wirksamer
Kontrollmechanismen) ist dabei zentral (vgl. ISO 42001, Abschnitt
6.1). Über die ISO 23894 wird konkretisiert, wie dieser Prozess des
Risiko-Management im Detail abläuft.

## Zusammenfassung und Einschätzung
Ich hoffe dieser kurze Überblick ist hilfreich um zu verstehen, wie in
der ISO Welt Standards verkettet sind - man könnte fast sagen, wie sie
funktionale Einheiten bilden. Wir haben gesehen, dass das allgemeine
Risiko-Management aus ISO 31000 sich auf verschiedene Arten in ISO
42001 wiederfindet (PDCA, Risiko-Management-Anforderungen) und wie die
ISO 23894 die Brücke schlägt.

Manchmal ist das nicht leicht zu verstehen, denn wer nur ISO 23894
aufschlägt, der wird vielleicht erstmal verwirrt sein: Wie beschrieben
findet man hier im Wesentlichen Hinweise und Ergänzungen zur
ISO 31000. Daher empfiehlt es sich, systematisch vorzugehen:
* Wer vom Risiko-Management kommt und in die KI einsteigen will, der
  wird ISO 31000 vielleicht schlicht in Verbindung mit ISO 23894 lesen
  und findet einen guten Überblick über die "KI-Knackpunkte".
* Wer von der Technik her kommt, der liest besser ISO 31000 vorab und
  erst im zweiten Schritt in Verbindung mit ISO 23894. Hat man 31000
  erst einmal verstanden, so werden KI-Experten vieles aus der ISO
  23894 als logisch, wenn nicht gar naheliegend, empfinden.

Auf jeden Fall hat es die ISO geschafft, hier **zwischen generischem
Risiko-Management und KI eine erste Brücke** zu schlagen. Das **reicht
natürlich nicht**. Denn KI ist eine Technologie und die Risiken von KI
in der Medizinbranche und in sozialen Netzen können sich doch auch
stark unterscheiden.

Allerdings: Es ist ein Start, der Experten von beiden Seiten
hoffentlich den Einstieg erleichtert.
