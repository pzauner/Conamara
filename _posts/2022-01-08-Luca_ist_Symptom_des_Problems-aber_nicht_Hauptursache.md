---
layout: post
title:  "Gesundheitsamt und Polizei kooperieren, Luca liefert die Daten (as intended)"
---

Der SWR berichtete heute darüber, dass die Polizei und das Gesundheitsamt Mainz gemeinsam Kontaktdaten einer Gaststätte anforderten, um Zeugen im Zusammenhang mit einem Todesfall ausfindig zu machen:
https://www.swr.de/swraktuell/rheinland-pfalz/mainz/polizei-ermittelt-ohne-rechtsgrundlage-mit-daten-aus-luca-app-100.html

Während das Ganze nun natürlich einen negativen Eindruck auf luca macht, so muss man gestehen: Mit der Zettelwirtschaft wäre dasselbe passiert.
Die luca-App ist so aufgebaut, dass das Gesundheitsamt gemeinsam mit der Betreiberin einer Lokalität oder Veranstaltung (Event) die entsprechenden Kontaktlisten einsehen kann. Das Problem in diesem Fall ist aber nicht unmittelbar luca, die die Daten weitergeben haben. Denn genau das ist Zweck von luca: Die gespeicherten Daten auf Anfrage an das Gesundheitsamt weiterzuleiten, wenn die Betreiberin die Weiterleitung bestätigt. Das Gesundheitsamt hat dabei einen Schlüssel, um die Daten zu entschlüsseln. Insofern: Works as intended.

Das eigentliche Problem besteht aus zwei Aspekten:
1. Polizei und Gesundheitsamt halten sich nicht an das Konzept Rechtsstaat
2. Die Daten fallen überhaupt an, obwohl sie es für den Zweck der Kontaktverfolgung (bei hinreichender Kooperation der zu Informierenden) nicht müssten (Stichwort Erforderlichkeit)

Problem 1: 
Dass die Polizei Interesse an zu nutzenden Daten zur Aufklärung hat, ist nichts Neues und war bereits vor der Ausformulierung des zulässigen Zwecks der Kontaktnachverfolgung im IfSG bekannt (https://www.haufe.de/compliance/recht-politik/polizeizugriff-auf-corona-gaestelisten-der-gastronomie-unzulaessig_230132_522174.html). Eben darum wurde auch das IfSG angepasst, sodass eine Nutzung der anfallenden Daten nur zum Zweck der Kontaktnachverfolgung im Zusammenhang mit Covid-19-Infektionen zulässig ist. Dies geschah am 19.11.2020 im Rahmen des dritten Gesetzes zum Schutz der Bevölkerung bei einer epidemischen Lage von nationaler Tragweite. (https://www.buzer.de/gesetz/14233/a254526.htm)
So regelt von dann an § 28a, Abs. 4 des IfSG, dass die Daten zur Kontaktnachverfolung nur »erhoben und verarbeitet werden, [dürfen] soweit dies zur Nachverfolgung von Kontaktpersonen zwingend notwendig ist.«

Nun kooperierten allerdings die Polizei (die aufgrund der Verschlüsselung der Daten auch gar keinen Zugriff auf die luca-Daten hätte) und das Gesundheitsamt, wobei das Gesundheitsamt die Betreiberin der Lokalität bat, die entsprechenden Daten in luca freizugeben. Das Gesundheitsamt erhält die Daten, (der Betreiberin ist in diesem Zusammenhang vielleicht auch ein Vorwurf zu machen, aber sicherlich kein großer) und gibt sie weiter an die Polizei.
Da hierzu aber jede Rechtsgrundlage fehlt, war die Datenverarbeitung unzulässig. Ebenfalls wird die Verwendung zu anderen Zwecken in den FAQs des Landes RLP ausgeschlossen: https://corona.rlp.de/de/service/luca-app/
Vor der Änderung des IfSG wurden jedoch belegterweise Daten zur Strafverfolgung an polizeiliche Behörden weitergegeben, wie etwa ein Artikel des Tagesspiegels aus dem Sommer 2020 belegt. (https://www.tagesspiegel.de/politik/faelle-aus-fuenf-bundeslaendern-bekannt-polizei-nutzt-kontaktdaten-aus-restaurants-auch-zur-strafverfolgung/26056130.html)

Allerdings gilt auch dann, wenn man unterschreiben würde, dass der Zweck der Strafverfolgung legitim ist und anfallende Daten stets zu sämtlichen guten Zwecken verwendet werden sollten, die Einhaltung rechtsstaatlicher Grundlagen. So ist es beispielsweise ein essentieller Bestandteil des Rechtsstaats die Rechtssicherheit. Der Bürger muss vorhersehen können, welche Konsequenzen sein Handeln bringt. Ebenso gilt der Grundsatz der Gesetzmäßigkeit, dass Handlungen einer gesetzlichen Grundlage bedürfen (https://www.bpb.de/nachschlagen/lexika/pocket-politik/16548/rechtsstaat) Es hätte sich beschließen lassen, dass die Daten auch zu anderen Zwecken verarbeitet werden hätten können, doch wurde diese Möglichkeit weder dokumentiert (§ 28a, Abs. 7, Nr. 8 IfSG), noch außerhalb des zur Kontaktnachverfolgung notwendigen Kontexts gewährt (§ 28a, Abs. 4). Ebenso bleibt das Urteil aus, ob selbst bei angepasster Gesetzeslage, diese Bestand hätte. https://kripoz.de/2020/11/26/die-verwendung-von-corona-gaestelisten-zur-strafverfolgung/ (-> Sowohl die Erforderlichkeit als auch die Verhältnismäßigkeit sind anzuzweifeln)

Problem 2:
Den Behörden vertrauen müssen. Während es zwar möglich sein kann, dass die Daten nicht missbraucht (etwa durch den Zugriff ohne Rechtsgrundlage wie in diesem Fall) werden, so wäre die ideelle Lösung, dass Missbrauch von Vornherein ausgeschlossen ist. Wenn der Zweck die Kontaktnachverfolgung ist, so kann dies auch über eine dezentrale Möglichkeit wie die der Corona-Warn-App geschehen. Da hier nicht nur a) niemand persönliche Daten hinterlegen kann, geschweige denn muss, ist es gar nicht möglich, die anfallenden Daten weitergehend zu missbrauchen. Im Falle von festen Veranstaltungen mit entsprechendem QR-Code https://www.coronawarn.app/en/faq/#check_in_implementation funktioniert die Kontaktnachverfolgung wie folgt:
Ist eine Person infiziert und lädt den Nachweis in die Corona-Warn-App so werden Konaktpersonen informiert, indem die eigenen Veranstaltungen auf den Server hochgeladen werden. Dabei bedarf es nicht der Information, wer konkret bei der Veranstaltung teilnahm, sondern nur, *dass* jemand teilnahm. Personen, die dann zur selben Zeit an der Veranstaltung teilgenommen haben, werden darüber informiert, indem das eigene Gerät prüft, ob die heruntergeladenen Kontaktmöglichkeiten mit den eigenen Teilnahmen an Events übereinstimmen. Ist das der Fall, erscheint die rote Warnung.
Kooperieren hier alle Personen (gewissenhafte Check-Ins, PCR-Test bei roter Warnung und hochladen von PCR-Ergebnissen), so ist diese Möglichkeit ebenso zur Kontaktverfolgung geeignet, wenn nicht der luca-Variante und besonders der analogen Zettel-Methode überlegen. Dafür spricht, dass es eben weder einer Inkenntnissetzung des Gesundheitsamts noch der Betreiberin des Events bedarf.

Medienberichte zum Thema:
- SWR https://www.swr.de/swraktuell/rheinland-pfalz/mainz/polizei-ermittelt-ohne-rechtsgrundlage-mit-daten-aus-luca-app-100.html
- Netzpolitik.org https://netzpolitik.org/2022/mainz-polizei-nutzte-luca-daten-von-kneipenbesuchern-ohne-rechtsgrundlage/

!(Archivierte / Gespiegelte Quellen als Download)[/assets/luca-2022-01-08.zip]
