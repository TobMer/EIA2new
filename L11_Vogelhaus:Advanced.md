# Aufgabe
Spendiere deinen Vögeln nun ein wenig mehr Intelligenz und sinnvolles Verhalten. Jeder Vogel, gleich welcher Art, soll zufällig ins Bild hineinfliegen, auf dem Boden unter dem Vogelhaus oder am Vogelhaus landen, dort etwas herumpicken und sich dann ein neues Anflugziel suchen, wo er wieder etwas verweilt und so weiter. Anflugziele können also das Vogelhaus sein, der Boden unter dem Vogelhaus, Orte außerhalb des Bildes oder weitere, die Du selbst wählst, wie zum Beispiel die Nase des Schneemanns.

Es soll zudem ein paar "dressierte" Vögel geben. Diese achten darauf, wo der Nutzer ins Bild klickt und fliegen dann in die Nähe dieses Punktes, wo sie verweilen und herumpicken und auf den nächsten Klick warten.

# Konzeption
Überlege, welche Informationen und Fähigkeiten ein Vogel nun zusätzlich braucht und was er sich merken muss. Auf was muss er reagieren? Wie kommt er von einem Punkt zum anderen, wie merkt er, dass er angekommen ist? Wann und warum fliegt er wieder weg? Erfasse dies in einer Erweiterung deines Klassendiagramms und entwirf die Algorithmen in den Erweiterungen deiner Aktivitätsdiagramme.

# Produktion
Erweitere deinen Code entsprechend. Implementiere dabei auch die passenden Sichtbarkeitsmodifikatoren sowohl bei den neuen, wie auch den bestehenden Programmteilen. Verwende, wo geeignet, Aufzählungstypen. die Schlüsselworte `abstract` und `static` sowie Zugriffsfunktionen.

# Hinweis
Halte dich nicht lange mit dem gezielten Flug zu einer Position auf. Eine sehr simple Methode ist es, bei jeder Bildwiederholung durch Subtraktion der aktuellen Position von der Zielposition einen Vektor zu berechnen, und dann die aktuelle Position um einen Bruchteil dieses Vektors zu verändern. Das ergibt eine schon fast organisch wirkende Bewegung, da das Objekt seine Startposition mit großer Geschwindigkeit verlässt und seine Zielposition stetig langsamer werdend ansteuert. Beachte aber, dass es die Zielposition nie ganz erreicht, da es immer nur um einen Bruchteil des Weges dorthin fortbewegt. [Vergleiche Achillesparadoxon](https://de.wikipedia.org/wiki/Achilles_und_die_Schildkr%C3%B6te)