# Konzeption
Erstelle für jede Klasse ein kleines Blockdiagramm, in dem Du den Namen der Klasse, alle erforderlichen Attribute mit Datentypen und die Methoden mit Typ des Rückgabewertes und ggf. der Parameterliste einträgst. Allerdings werden die Parameterlisten jetzt zum größten Teil überflüssig, da die Objektmethoden direkt auf die Objekteigenschaften zugreifen können! Es sollen nur Parameter übergeben werden, wenn die entsprechende Information nicht sinnvoll eine Eigenschaft des Objektes darstellt. Achte darauf, dass eine Klasse auch nur eine Instanz und nicht ganze Gruppen beschreibt. 

Erstelle vollständige Aktivitätsdiagramme für die Bewegungsmethoden der Objekte!

# Produktion
Implementiere die Klassen in eigenen Dateien und entferne den nun überflüssigen Code aus dem Hauptprogramm. Implementiere die Methoden zum Zeichnen und Bewegen als Objektmethoden in den Klassen. Du kannst teilweise leicht deine bereits erstellten Methoden in die Klassen verschieben und modifizieren. Das Hauptprogramm soll nicht mehr die Details der einzelnen Objekte kennen müssen um sie zu verwalten, sondern nur noch deren Methoden aufrufen.

# Optimierung
Der Hintergrund mit stillstehende Objekten soll nur einmal bei Programmstart gezeichnet und dann gespeichert werden (siehe Hinweise unten). Hiermit kannst Du bei jedem Animationsframe den Hintergrund restaurieren ohne das jedesmal aufwendige Zeichenbefehle abgearbeitet werden müssen nur um wieder den gleichen Hintergrund zu erzeugen.

# Recherchehinweise
- getImageData
- putImageData