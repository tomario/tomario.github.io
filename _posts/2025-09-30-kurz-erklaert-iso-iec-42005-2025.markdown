---
layout: post
title: "ISO/IEC 42005 kurz erklärt: Eine Brücke zwischen Governance & Systemebene?"
date: 2025-09-30
last_modified_at: 2025-09-30
categories: [Standards]
tags: [ISO 42001]
excerpt: "Ein kurzer Überblick über den neuen ISO/IEC 42005-Standard zum Impact-Assessment für KI-Systeme und die dadurch entstehende Brücke zwischen ISO 42001 und EU AI Act."
---

ISO 42005 ist die neueste Ergänzung zur 42000'er Serie der ISO,
die sich mit dem Management bzw. der Governance von Künstlicher
Intelligenz (KI) befasst. Der finale Standard wurde am 28. Mai 2025,
also diese Woche veröffentlicht.

Über [ISO
42001](/standards/2025/05/20/kurz-erklaert-iso-iec-42001-2023.html)
habe ich bereits berichtet. Hier und heute soll also darum gehen, wie
ISO 42005 das bereits bestehende Governance-Framework von ISO 42001
ergänzt.

## Auf einen Blick

| **Standard** | [ISO/IEC 42005:2025](https://www.iso.org/standard/44545.html) |
| **Titel** | Information technology — Artificial intelligence — AI system impact assessment |
| **Typ** | Internationaler Standard |
| **Herausgeber** | ISO |
| **Status** | Veröffentlicht |
| **Wesentliche Inhalte** | Beinhaltet Richtlinien und Hinweise für die strukturierte Evaluierung möglicher Auswirkungen von KI-Systemen auf Individuen und die Gesellschaft. |

## ISO 42005 - eine (gewisse) Detaillierung von ISO 42001
ISO 42001 ist entlang der Logik *Plan, Do, Check, Act*
aufgebaut. Kapitel 6.1 beschreibt die organisatorischen Komponenten,
die für ein KI-Risikomanagement notwendig sind.

Wie vielfach festgestellt beschreibt ISO 42001 die KI-Governance dabei
vor allem auf einer organisatorischen Ebene. Den Autor:innen war
jedoch klar: Risiken manifestieren sich natürlich in den Produkten,
die KI beinhalten - egal ob man diese einsetzt, oder selbst
entwickelt. Zwar fällt dieser Punkt nicht direkt ins Auge – übersehen
wurde er aber keinesfalls. Kapitel 6.1.4 der ISO 42001 führt aus, dass
Organisationen einen Prozess etablieren müssen, um mögliche
Konsequenzen von Entwicklung, Deployment oder Einsatz eines KI-Systems
für Individuen und Gesellschaft zu beurteilen. Dies ist das *AI system
impact assessment*.

Die Ergebnisse dieses Assessments wiederum müssen dokumentiert werden
und in das Risikomanagement zurückfließen. Hier werden sie 'ganz
normal' behandelt, also beispielsweise mit Maßnahmen der
Risiko-Minimierung hinterlegt, vielleicht aber auch sehenden Auges
akzeptiert. Dies hängt natürlich auch von dem erwarteten *Impact* und
anderen Faktoren ab. An dieser Stelle also erstmal nichts Neues. 

Was nun neu ist: ISO 42005 beschreibt, wenn auch eher oberflächlich,
die wichtigsten Komponenten eines solchen *AI system impact
assessments*.

## Inhalte der Norm
Doch werfen wir zunächst einmal einen Blick in die Inhalte der Norm.

{% include figure.html preview="/assets/images/iso-42005-ueberblick-klein.png" full="/assets/images/iso-42005-ueberblick.png" alt="Überblick ISO 42005" caption="Abbildung: Überblick ISO/IEC 42005 – zum Vergrößern klicken" %} 

#### Hauptteil
Der inhaltliche Teil des Standards gliedert sich in zwei wesentliche
Teile:

* Hinweise zur **Implementierung des Assessment-Prozesses** und
* Hinweise zur **Dokumentation des Assessments**

Ich habe mich für den Begriff *Hinweis* entschieden, da der Standard
häufig eher zu klärende Punkte aufwirft, als diese zu lösen.

Was ist damit gemeint? Für die Hinweise zur **Implementierung des
Assessment-Prozesses** etwa werden wichtige Aspekte eines solchen
Prozesses aufgelistet. Hierzu zählen das Timing (also wann und wie oft
ein Assessment durchgeführt werden soll) und die Notwendigkeit, den
Scope des Assessment zu bestimmen (was genau ist das betrachtete
System?). Diese Punkte sind häufig offen formuliert, so erläutert der
Standard meist eher die Faktoren, die eine Antwort bestimmen - nicht
aber die Antwort selbst. Das Timing ist etwa von rechtlichen
Anforderungen, dem Risiko-Level des KI-Systems,
Stakeholder-Anforderungen etc. abhängig.

Interessierte Leser finden also gute Aufzählungen von relevanten
Faktoren, allerdings wenig greifbares, um die eigenen internen
Richtlinien festzulegen.

Ähnlich ist es für den Abschnitt zur **Dokumentation des
Assessments**, der vor allem zu betrachtende Faktoren wie etwa Scope,
Systembeschreibung, (un-)vorgesehene Verwendung des Systems
etc. auflistet. Auch hier liegt der Schwerpunkt eher auf einer doch
relativ vollständig wirkenden Auflistung von Faktoren, ohne aber in
die Details zu gehen.

Was viele als möglicherweise zu oberflächlich ansehen hat aus meiner
Sicht aber doch einen Wert: Insbesondere Checklisten und
Best-Practices können mit diesen Informationen auf eine gewisse
Vollständigkeit (im Sinne von ISO 42005) geprüft werden.

Ein Blick in das (öffentlich) verfügbare
[Inhaltsverzeichnis](https://www.iso.org/obp/ui/en/#iso:std:iso-iec:42005:ed-1:v1:en)
zeigt auch weitere spannende Faktoren, z.B. die Notwendigkeit,
Datenqualität und die verwendeten Algorithmen genauer zu beleuchten.

Wie ich in einem zukünftigen Beitrag hoffentlich nochmal genauer
ausführen kann: Beim KI-Einsatz ist es ebenso entscheidend, die eigene
Rolle in Bezug auf das betrachtete KI-System zu berücksichtigen. Diese
Rolle, wird in vielen Frameworks explizit betrachtet (z.B. mit dem
Konzept des Duty Holders im [IEEE CertifAIEd
Framework](https://standards.ieee.org/products-programs/icap/ieee-certifaied/professional-certification/)). Im
"ISO-KI-Universum" muss man einen Blick in den Standard [ISO/IEC
22989:2022](https://www.iso.org/standard/74296.html) werfen. In
Abschnitt 5.19 werden die hier so genannten *Stakeholder Roles*, wie
etwa *AI Provider* oder *AI Producer* genauer spezifiziert.

#### Die Anhänge
Die Anhänge haben zwar allesamt einen informativen Charakter, sie sind
aber doch sehr hilfreich. Einige Aspekte die hier beleuchtet werden
umfassen:

* Sehr nützliche Hinweise zur Nutzung von ISO 42005 in Verbindung mit
  * [ISO 42001](https://www.iso.org/standard/81230.html), dem
    KI-Management-System, und
  * [ISO 23894](https://www.iso.org/standard/77304.html), den
    Hinweisen zum Risiko Management für KI. ISO 23894 ist eine
    Verbindung zwischen dem in ISO 42001 geforderten Risiko-Management
    und den *allgemeinen* Risiko-Management-Vorgaben der ISO, wie sie
    in [ISO 31000](https://www.iso.org/standard/65694.html) festgelegt sind.
* Praktische Hinweise zum Alignment der ISO-42005-Assessments mit
  anderen, üblichen Assessments, wie etwa dem Privacy-Assessment. Die
  Autor:innen möchten hier also Synergien skizzieren.
* Template-Beispiele für die Assessment-Durchführung. 

## Warum dieser Standard relevant ist
Ich habe erst kürzlich mit einer sehr geschätzten Kollegin
gesprochen, die ISO 42005 nicht sehr viel abgewinnen wollte. Der
Ansatz, so berichtete sie, sei eher von "Rechtsanwält:innen" als von
Menschen aus der Praxis entwickelt worden. Man muss ihr recht geben -
in der Tat wäre es schön gewesen, im Anhang tatsächlich ein _echtes_
Template zu finden - nicht nur (unverbindliche) Beispiele, wie ein
solches aussehen könnte.

Dennoch muss man dem Standard eine Sache lassen: Die aufgezählten, zu
betrachtenden Aspekte eines Impact-Assessments sind relevant und
erlauben es aus meiner Sicht sehr gut, existierende Ansätze auf
Vollständigkeit zu prüfen und somit aufzuzeigen, wie sie den
Anforderungen der ISO 42001 gerecht werden.

ISO 42005 kann man auch als ein Scharnier zwischen Organisations- und
System-Ebene sehen: Der EU AI Act betrachtet ja insbesondere
*bestimmte Risiken*, die sich aus dem Einsatz von KI ergeben können. 
* Die ISO definiert Risiken als Effekte von Unsicherheit, im Guten wie
  im Schlechten, die es zu managen gilt.
* Die EU und der EU AI Act fokussieren auf das [Risiko eines
  Schadens](https://artificialintelligenceact.eu/de/article/3/), das
  ist im Wesentlichen eine Untermenge der Risiken nach ISO.

Es ist hier also wichtig festzuhalten: Ein ISO-basiertes
Risiko-Management sieht Produktrisiken durchaus, hat aber einen
breiteren Fokus. Dieser breitere Fokus ist wichtig, denn
**wirtschaftlicher Erfolg bedeutet auch, positive Effekte von
Unsicherheit strategisch zu nutzen**.

Für Organisationen, die KI gesamthaft mit ISO 42001 managen wollen,
dient ein solches ISO 42005 basiertes Impact-Assessment also vor allem
auch dazu, die möglichen gesetzlichen Auflagen zu verstehen. Das ist
dann genau der [Risiko basierte
Ansatz](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)
des EU AI Acts.

## Persönliche Einschätzung
Das eigentliche Blog-Thema diese Woche sollten [IEEE 7000 aka. ISO
24748-7000](https://standards.ieee.org/ieee/24748-7000/11098/) und
[Value-based Engineering (VBE)](https://value-based.engineering)
sein. VBE ist ein ganz praktischer Ansatz, wie man bei der
IT-System-Entwicklung insbesondere rechtliche und soziale
Anforderungen berücksichtigt. Aus meiner Sicht ergänzen sich ISO
42005 und VBE durchaus. Ein einfaches Beispiel: Die
System-Modellierung *System-of-Interest* und *System-of-Systems*
spiegelt sich eins-zu-eins in ISO 42005 wider. Ich sehe den
abstrakteren Charakter der Norm also auch als eine Chance, bestehende
Ansätze zu integrieren.

Neben der Veröffentlichung von ISO 42005 möchte ich auch einen zweiten
Zufall teilen: Diese Woche habe ich die [Konferenz zum Digitalen
Humanismus](https://digitalhumanism.at/digihum-25/) in Wien
besucht. Natürlich war dort, in Fachkreisen, auch Standardisierung das
Thema. Wie im Beitrag zu [ISO
42001](/standards/2025/05/20/kurz-erklaert-iso-iec-42001-2023.html)
beschrieben, ist die Konkurrenz zwischen den
Standardisierungs-Organisationen groß. *Standardisieren heißt Konsens
bilden*. Konkretere Ansätze aus ISO 42005 wären sicherlich
hilfreich. Insofern bin ich sehr gespannt, ob ein größerer Kompromiss
im europäischen Kontext gelingt. Bis dahin haben wir nun aber erstmal
eine solide Baseline.
