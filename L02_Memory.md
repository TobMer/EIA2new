# Aufgabe
Konzipiere ein Memoryspiel als Web-App für Desktoprechner, Tablets und Smartphones, das von bis zu vier Spieler am gleichen Gerät gespielt werden kann, wobei die Spieler sich bei ihren Zügen abwechseln.

Die Anzahl der Kartenpaare (5 - 25) und der Spieler (1-4), sowie letzterer Namen, sind variabel und werden von einem der Spieler zu Spielbeginn bestimmt. Die Karten werden als kleine Quadrate dargestellt, die alle die gleiche Rückseite zeigen, im einfachsten Fall schlicht eine Farbe. Die Inhalte der Karten, sozusagen deren Vorderseite, können einfach Zahlen, Buchstaben oder Begriffe sein. Damit werden die Paare gebildet, jedes Paar darf aber nur einmal im Spiel auftauchen. Die Karten werden wie beim richtigen Memory bei jedem Spiel zufällig neu verteilt. Sie ändern während des Spiels nicht ihre Position, werden gegebenenfalls aber entfernt. Der Spieler am Zug kann zwei Karten aktivieren, woraufhin deren Vorderseite dargestellt wird. Während zwei Karten aufgedeckt sind, ist keine weitere Interaktion möglich. Dieser Zustand soll etwa zwei Sekunden dauern. Dann verschwinden die Karten, sofern ihre Inhalte gleich sind, und der Punktestand des Spielers wird um 1 erhöht. Ungleichheit werden wieder die Rücken angezeigt, der Spieler erhält keine Punktestanderhöhung und der nächste Spieler ist am Zug. Sind alle Karten verschwunden, erscheint eine Gratulation für den Spieler mit der höchsten Punktzahl. Alle Spieler fangen mit 0 Punkten an. Die aktuelle Punktzahl ist für jeden Spieler jederzeit einsehbar und eindeutig zugeordnet.

# Vorgehensweise
Halte dich strikt an die in der Lektion geübte Reihenfolge und Syntax der Konzeption. Halte zudem den geplanten Aufbau der CSS-Formatvorlage fest.

# Recherche
Es könnte sehr hilfreich sein, wenn Du folgende Methoden und Attribute einiger Javascript-Objekte näher untersuchst:
- Math.random()
- Array.splice(...)
- Element.className