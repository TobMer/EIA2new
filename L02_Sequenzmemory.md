# Aufgabe
Konzipiere ein kleines Memoryspiel als Web-App für Desktoprechner, Tablets und Smartphones, bei dem sich ein Spieler die zufällige Position von Zeichen merken und diese in einer bestimmten Reihenfolge aktivieren muss, nachdem sie verdeckt wurden.

Zu Beginn einer Spielrunde kann der Spieler selbst eine Sequenz eingeben oder wählen, dass er mit einer von 10 (oder mehr) vordefinierten Sequenzen spielen will. Eine solche Sequenz könnte beispielsweise die Zeichenkette "EIA2-Inverted" sein. Weiterhin kann er die Zeit angeben, die ihm für die Spielrunde zur Verfügung steht und die Zeit, die ihm die zufällig durchmischte Zeichenfolge zu Rundenbeginn gezeigt wird. Im Beispiel könnte diese durchmischte Folge derart aussehen: "vAntIde-2IEre".

Dann startet die Runde und die Zeichenfolge wird für die Dauer der angegebenen Zeit gezeigt, eine Interaktion ist in dieser Zeit nicht möglich. Dann werden die Zeichen, an gleicher Position verharrend, verdeckt. An ihrer Stelle sind nun gleichfarbige und gleichförmige Flächen zu sehen, die per Klick oder Touch aufgedeckt werden können. Aufgabe des Spielers ist es nun, die Zeichen in der korrekten Reihenfolge der Ausgangssequenz aufzudecken. Im Beispiel muss er also zuerst die Fläche an der Position des "E" aufdecken, dann eines der großen "I"s, dann das "A" usw. Verlässt der Spieler die korrekte Sequenz indem er eine falsche Fläche aktiviert, erhält er für zwei Sekunden ein sinnvolles optisches Feedback, danach werden alle Flächen wieder verdeckt. Innerhalb der vorgegebenen Zeit muss er die Sequenz vollständig aufdecken, sonst gilt das Spiel als verloren. Gelingt es ihm aber, erhält er positives optisches Feedback. Während des Spiels werden die Zeiten, rückwärts laufend, in Sekunden auf dem Bildschirm angezeigt.

# Vorgehensweise
Halte dich strikt an die in der Lektion geübte Reihenfolge und Syntax der Konzeption. Halte zudem den geplanten Aufbau der CSS-Formatvorlage fest. Achte sehr darauf, dass Du nicht lediglich die Aufgabenstellung in anderer Form wiederholst, sondern dass Du eine klare und mit der bislang in dieser Modulreihe geübten Technik durchführbare Lösung konzipierst. Eine andere mit der Technik vertraute Person muss anhand deiner Konzeption das Programm kodieren können, ohne über viel mehr als die reine Umsetzung in Code nachzudenken. Tatsächlich ist es eine äußerst effektive Übung, wenn Du das Konzept einer anderen Person umsetzt und dabei mit ihr über die Klarheit und Sinnhaftigkeit des Entwurfs diskutierst.

# Recherche
Es könnte sehr hilfreich sein, wenn Du folgende Methoden und Attribute einiger Javascript-Objekte näher untersuchst:
- Math.random()
- Array.splice(...)
- Element.className