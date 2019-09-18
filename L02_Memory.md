### Aufgabe
Konzipiere ein Memoryspiel als Web-App für Desktoprechner, Tablets und Smartphones, das von bis zu vier Spieler am gleichen Gerät gespielt werden kann, wobei die Spieler sich bei ihren Zügen abwechseln.

Die Anzahl der Kartenpaare (5 - 25) und der Spieler (1-4), sowie letzterer Namen, sind variabel und werden von einem der Spieler bestimmt. Die Karten werden als kleine Quadrate dargestellt, die alle die gleiche Rückseite zeigen, im einfachsten Fall schlicht eine Farbe. Die Inhalte der Karten, sozusagen deren Vorderseite, können einfach Zahlen, Buchstaben oder Begriffe sein. Damit werden die Paare gebildet, jedes Paar darf aber nur einmal im Spiel auftauchen. Die Karten werden wie beim richtigen Memory bei jedem Spiel zufällig neu verteilt. 

In einem anderen Bereich erscheint für jeden Spieler eine Identifikation (z.B. "Spieler 1") und dazu eine Punktezahl, welche sich im späteren Verlauf des Spieles ändern kann.

### Vorbereitung
Setzen Sie sich zunächst intensiv mit dem Code aus der Vorlesung auseinander. Er wurde ein wenig ergänzt und aufgehübscht. Stellen Sie sicher, dass Sie sämtliche dort behandelte Ereignisse ausgelöst und die Ausgaben in der Konsole erklären können. Widmen Sie sich erst dann den untenstehenden Aufgabenteilen.  
_PS: dass in Chrome beim aufgeklappten Event unter currentTarget immer null erscheint, ist wohl ein aktueller Browser-Bug_

### Aufgabe
Bei Klick auf einen verdeckten Kartenrücken wird der Inhalt angezeigt. Dasselbe geschieht bei Klick auf einen zweiten Kartenrücken. Dann werden die Inhalte verglichen und bei Gleichheit verschwinden die Karten. Bei Ungleichheit werden wieder die Rücken angezeigt. Während beide Karten aufgedeckt sind, ist keine Interaktion möglich. Dieser Zustand soll etwa zwei Sekunden dauern. Sind alle Karten verschwunden, erscheint eine Gratulation!

### Konzeption
Halten Sie in der Layout-Skizze fest, an welchen Stellen Sie Event-Listener installieren. Erstellen Sie Aktivitätsdiagramme für die Erweiterungen Ihres Codes der vorangegangenen Aufgabe. Suchen Sie hierfür zunächst die Knotentypen "Signalempfang" (Receive Signal Action, Accept Event Action) und "Zeitereignis empfangen" (Time Event, Accept Time Event Action) im Internet und nutzen Sie diese als Startknoten für die Handler.  

### Programmierung
Setzen Sie Ihr Konzept syntaktisch korrekt und mit Hilfe des vorgegebenen Coding-Styleguides um.

Die aufzurufende HTML-Datei enthält nur einen Header mit dem Verweis auf ihr Skript, sowie die beiden Bereiche für die Karten und die Spielerinformation. Die Stil-Informationen zur Anzeige des aufgebauten DOM sind vollständig in der CSS-Datei hinterlegt, also auch für die Erscheinungen der Karten in den Zuständen verdeckt, offen und genommen (hidden, open, taken). Zur entsprechenden Anzeige muss also nur ein Attribut des Kartenelements geändert werden.

Die aufgebaute Seite soll sowohl auf Smartphones, wie auf Tablets und Desktop-Geräten vernünftig dargestellt werden.  

### Konzeption
Entwerfen Sie zunächst eine Skizze, welche die Darstellung der Seite im vollständig aufgebauten Zustand darstellt. Weisen Sie dort bereits auf die zu verwendenden HTML-Elemente hin. Stellen Sie dann für die Elemente Stilvorgaben zusammen. Erstellen Sie schließlich ein oder mehrer Aktivitätsdiagramm für das TypeScript-Programm.

### Programmierung
Setzen Sie Ihr Konzept syntaktisch korrekt und mit Hilfe des vorgegebenen Coding-Styleguides um.  

### Recherche
Es könnte sehr hilfreich sein, wenn Sie folgende Methoden und Attribute einiger Javascript-Objekte bzw. Klassen näher untersuchen:
- Math.random()
- Array.splice(...)
- Element.className

