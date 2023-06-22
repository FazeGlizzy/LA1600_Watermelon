# Projekt-Dokumentation


Warermelon/Salie, Spaqi, Heiniger, Müller

| Datum | Version | Zusammenfassung                |
| ----- | ------- | ------------------------------ |
| 11.05 | 0.0.1   | Projektdokumentation erstellt. |
| 15.06.23      | 0.1.0     |  Prototyp fertig                              |
|   22.06.23    | 1.0.0   |  Website für den Release fähig, jedoch noch nicht 100% fertig.   |

## 1 Informieren

### 1.1 Ihr Projekt

Wir erstellen als Gruppe eine Website, in welcher man zuden Themen Mathe, Deutsch und Englisch Aufgaben lösen kann.

Das Ziel ist es eine Webseite zu erstellen und diese per Github online zu stellen. Die Webseite sollte CSS only sein mit dem Ziel uns am Ende des Projektes gut mit CSS auszukennen. Natürlich wir die Website nicht nur mit CSS geschrieben sondern auch mit Html.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ       | Beschreibung                                                                                       |
| ---- | --------------- | --------- | ---------------------------------------------------------------------------------------------------|
| 1    | Kann            |Qualität   |Als ein User möchte ich auf der Homepage von einer professionellen Slideshow begrüsst werden        |
| 2    | Muss            |Funktional |Als ein User möchte ich mit dem Hamburger Menu auf Mobilen Geräten Navigieren können                |
| 3    | Kann            |Funktional |Els ein Lehrnender möchte ich Ankreuzen können welche Ziele ich heute abgeschlossen habe            |
| 4    | Kann            |Qualität   |Als ein User möchte ich über Bilder Hovern können, die dann grösser werden                          |
| 5    | Muss            |Funktional |Als ein Lehrnender möchte ich Lehrnkarten haben die sich drehen wenn ich draufklicke                |
| 6    | Muss            |Funktional |Als ein Lehrnender möchte ich ein Leseverstehen bei welchem ich Fragen beantworten kann. (DE)       |
| 7    | Muss            |Funktional |Als ein Lehrnender möchte ich ein Leseverstehen bei welchem ich Fragen beantworten kann. (EN)       |

### 1.3 Testfälle

| TC-№ | Ausgangslage            | Eingabe      | Erwartete Ausgabe                                     |
| ---- | ----------------------- | -------------| ------------------------------------------------------|
| 1.1  |Website geöffnet         |Homepage      |Eine Slideshow wird angezeig                           |
| 2.1  |Auf Mobilem gerät        |Auf einer Site|Die Navigation wir zu einem Hamburger Menu             |
| 3.1  |Auf einer Unterseite     |klicken       |Beim klicken auf ein Lehrnziel wird es durchgestrichen |
| 4.1  |Mauszeiger auf einem Bild|Hover         |Das Bild wird ein bisschen grösser                     |
| 5.1  |Auf einer Unterseite     |Klick         |Karte kehrt sich um                                    |
| 6.1  |Auf der DE Seite         |Lesen         |Richtig oder Falsch                                    |
| 7.1  |Auf der EN Seite         |Lesen         |Richtig oder Falsch                                    |

### 1.4 Diagramme

Skizze der der Website
![Screenshot 2023-05-11 100747](https://github.com/FazeGlizzy/LA1600_Watermelon/assets/111046378/05099e08-813f-4beb-8804-c266b280695e)
![Screenshot 2023-05-11 100816](https://github.com/FazeGlizzy/LA1600_Watermelon/assets/111046378/564f6556-f0fd-49fd-9673-3db04170352e)
![Screenshot 2023-05-11 100841](https://github.com/FazeGlizzy/LA1600_Watermelon/assets/111046378/76c3ad6b-5dd5-4bd2-9ddd-21cae92c0838)
![Screenshot 2023-05-11 100947](https://github.com/FazeGlizzy/LA1600_Watermelon/assets/111046378/8ab2566e-918f-453d-8eb9-5cd58e7eb9b1)


Use Case-Diagramm

![image](https://github.com/FazeGlizzy/LA1600_Watermelon/assets/111046378/6cc2c07b-b625-4356-9bb9-0a3eff4454e4)



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 11.05 |  Steven   |  Erstellen einer SlideShow   |    ca 1h           |
| 1.B  | 18.05 |  Steven   |   SlideShow fertigstellen           | ca 1h              |
| 1.C  | 18.05 |  Steven   |   SlideShow anpassen          | ca 45min              |
| 5.A  | 11.05 |  Steven   |  Erstellen der Karteikarten   |    ca 1h           |
| 5.B  | 11.05 |  Steven   |  Fertigstellen einer Karteikarten   |    ca 1h           |
| 2.A  | 11.05 |  Yanik    |  Erstellen der Navigation            |  ca. 45min             |
| 2.B  | 18.05 |  Yanik    |  Erstellen der Burger Menus           | ca. 45min            |
| 2.C  | 18.05 |  Yanik    |  Die Media Querrys einstellen           | ca. 45min            |
| 2.D  | 18.05 |  Yanik    |  Die Navigation gestalten/anpassen           | ca. 45min            |
| 4.A  | 11.05 |  Yanik    |  Erstellen der Hovereffekte für Bilder           |  ca. 1h            |
| 4.B  | 11.05 |  Yanik    |  Fertigstellen der Hovereffekte für Bilder           |  ca. 1h            |
| 6.A  | 11.05 |  Lukas    |  Text einfügen wie auch die Fragen          |  ca. 45min             |
| 6.B  | 18.05 |  Lukas    |  Erstellen der abfrage Box           | ca. 45min            |
| 6.C  | 18.05 |  Lukas    |  Richtig/Falsch eingaben einstellen           | ca. 45min            |
| 6.D  | 11.05 |  Lukas    |  Tägliche Ziele erstellen            |  ca. 45min             |
| 6.E  | 22.06 |  Lukas    |  Tägliche Ziele durchsteichen können            |  ca. 45min             |
| 3.A  | 18.05 |  Lukas    |  Animation bei fertigstellen der Ziele           | ca. 45min            |
| 7.A  | 11.05 |  Brandon    |  Text einfügen wie auch die Fragen          |  ca. 45min             |
| 7.B  | 18.05 |  Brandon    |  Erstellen der abfrage Box           | ca. 45min            |
| 7.C  | 18.05 |  Brandon    |  Richtig/Falsch eingaben einstellen           | ca. 45min            |
| 7.D  | 11.05 |  Brandon    |  Tägliche Ziele erstellen            |  ca. 45min             |
| 8.E  | 11.05 |  Brandon    |  Tägliche Ziele erstellen            |  ca. 45min             |
| 3.A  | 18.05 |  Brandon    |  Animation bei fertigstellen der Ziele           | ca. 45min            |
Total:



## 3 Entscheiden

Wir haben uns entschieden mit Visual Code zuarbeiten, da diese Software viele gute erweiterungs möglichkeiten hat. Zudem haben wir uns dazu entschieden, das jeder sein eigener Fokus in der Programmierung hat sprich Brandon und ich sind für die Leseverstehen zuständing Yanik für das Hamburgermenu etc.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 11.05      | Steven          |   1h            |     angefangen              |
| 6.A  | 11.05/25.05       | Lukas          |  45min             |   50min                |
| 2.A  | 11.05      |  Yanik         |   45            |     angefangen              |
| 6.D  | 25.05      | Lukas          |  45             |       1h         |
| 6.A  | 25.05      | Lukas        |  45             |      45min           |
| 7.D  | 25.05      | Brandon          |  45             |       1h         |
| 7.A  | 25.05      |Brandon        |  45             |      45min           |
| 6.B  | 01.06      |Lukas       |  45             |      angefangen            |
| 6.C  | 01.06     |Lukas        |  45             |      angefangen           |
| 7.A  | 01.06      |Brandon        |  45             |      angefangen           |
| 7.A  | 01.06      |Brandon        |  45             |      angefangen           |
| 2.B  | 25.05      |  Yanik         |   45            |     1h              |
| 2.C  | 25.05      |  Yanik         |   45            |     angefangen              |
| 2.D  | 25.05      |  Yanik         |   45            |     45min            |
| 4.A  | 25.05      |  Yanik         |   45            |     45min              |
| 4.B  | 01.06      |  Yanik         |   45            |     angefangen              |
| 6.E  | 21.06      |  Lukas         |   45            |    2h          |
| 7.E  | 21.06      |  Ursprünglich Brandon/ gemacht Lukas         |   45            |    20min          |
| 7.B  | 21.06      |  Brandon       |   45            |    angefangen    |
| 6.B  | 21.06      |Lukas       |  45             |      30min           |
| 6.C  | 21.06      |Lukas       |  45             |      weitergemacht Probleme mit der Anzeige ca50min versucht           |
| 4.B  | 15.06      |  Yanik         |   45            |     2h             |

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 20.06.23|  funktioniert        | Lukas       |
| 2.1  | 20.06.23|  funktioniert           | Lukas        |
| 3.1  | 20.06.23| funktioniert   nicht         | Lukas        |
| 4.1  | 20.06.23| funktioniert   nicht         | Lukas        |
| 5.1  | 20.06.23| funktioniert   nicht          | Lukas        |
| 6.1  | 20.06.23| funktioniert   nicht          | Lukas        |
| 7.1  | 20.06.23| funktioniert   nicht          | Lukas        |
| 8.1  | 20.06.23| funktioniert   nicht          | Lukas        |
| 3.1  | 21.06.23| funktioniert     | Lukas        |


Fazit: Stand 20.06 ist die Website fast fertig jedoch fehle wichtige Elemente wie das Karten swappen etc.

## 6 Auswerten



## 7 Quellen
https://alvarotrigo.com/blog/hamburger-menu-css/
