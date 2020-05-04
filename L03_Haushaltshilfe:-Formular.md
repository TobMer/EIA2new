# Aufgabe
In der Corona-Krise herrschen schwierige Verhältnisse für uns alle, insbesondere für ältere Mitmenschen, die der Risikogruppe angehören. Ein System, das potentielle Helfer und Bedürftige zusammenbringt, könnte den Alltag erleichtern. So können Aufgaben, wie das Einkaufen, übernommen werden, damit die Leute das Haus nicht verlassen und sich unnötiger Gefahr aussetzen müssen. Die Hilfe wird von Freiwilligen übernommen, die sich auf der Plattform anmelden können.

Ihr habt nun die Aufgabe ein Webformular zu entwickeln in die Bedürftigen eingeben können, was sie benötigen.

Folgende Punkte sind zu beachten:
* Man sollte mehrere Erledigungen hinzufügen können, je nach Erledigung sollen unterschiedliche Informationen zu der Erledigung erscheinen.
* Beispiele :
    * Einkaufen
        * Es soll eine Liste mit vordefinierten Artikeln geben aus der sich der Nutzer seine eigene Liste zusammen stellen kann.
        * Hat der Nutzer einen Artikel ausgewählt, sollte er noch die Möglichkeit bekommen die Menge anzugeben.
            * Die Menge kann in verschiedenen Einheiten angegeben werden. (Gramm, Liter, Packung etc.)
        * Außerdem möchte der Nutzer eventuell auch angeben aus welchem Geschäft er diesen Artikel am liebsten haben möchte.
    * Haushaltsarbeiten (Rasenmähen, Wischen, Staubsaugen, Wände steichen etc.)
    * Post wegbringen
    * Pakete abholen (Nutzer kann aus einer Liste von Paketstationen wählen wo das Paket abgeholt werden muss)
    * Geld abheben
        * Es erscheint ein Slider mit dem ausgewählt werden kann wieviel Geld abgehoben werden soll.
* Jeder Punkt kostet einen gewissen Betrag an Geld, welcher sich bei jeder Änderung automatisch aktualisiert.
* Am Ende erhält der Benutzer eine Liste mit den Aufgaben die er in Auftrag gegeben hat und den Kosten die er dafür tragen muss.

Hier ein Beispiel wie eine solche Liste am Ende aussehen könnte:
***
### Erledigung 1
**Einkaufen**

Name des Artikels | Menge des Artikels | Einheit | Kosten | Angabe wo der Artikel gekauft werden soll
:---------------: | -----------------: | :------ | :----: | :---------------------------------------:
Brot | 1 | kg | 1.29€ |Aldi
Backmischung | 2 | Packungen | 2.32€ | Aldi
Wischmop (Aus dem Angebot) | 1 | Stück | 17,00€ | Rewe
Wasser | 2 | Sixpack | 3,00€ | -
Hackfleisch (gemischt) | 200 | Gramm | 4.60€ | - 

Name des Kostenpunkts | Betrag
:-------------------- | -----:
Kosten für die Artikel | 28,21€
Einkaufsgebühr | 10,00€
**Gesamt** | 38,21€


### Erledigung 2
**Geld abheben**

Menge: 50€

Beschreibung| Betrag
:-------------------- | -----:
Abgehobenes Geld | 50,00€
Gebühren | 5,00€
**Gesamt** | 55,00€

### Erledigung 3
**Wischen**

Beschreibung | Betrag
:----------- | ------:
3 Zimmer wischen | 10€ / Zimmer
**Gesamt** | 30€

***

Gesamtkosten | 123,21€
------------ | ------

***
