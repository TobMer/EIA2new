# L01_Boxes

1. Erstellen Sie eine Tracetable zu untenstehendem TypeScript-Code.
1. Stellen Sie die zu erwartende Ausgabe grafisch auf Papier dar.
1. Bringen Sie schließlich den Code zum Laufen und überprüfen Sie das Ergebnis.
1. Verfolgen Sie den Verlauf im Debugger. Bestimmen Sie Abweichungen zu Ihrer Erwartung und erklären Sie diese.
1. Versuchen Sie ein Aktivitätsdiagramm für den Programmablauf zu konstruieren. Nutzen Sie dafür das in der Veranstaltung ausgeteilte ([oder auch hier einsehbare](https://github.com/JirkaDellOro/EIA2/blob/master/ActivityDia2Code.pdf)) Merkblatt sowie das Beispiel aus der ersten Aufgabe.

```typescript
namespace Boxes {
	let n: number = 5;
	let c: string;
	let x: number = 0;
	let y: number = 0;

	for (let i: number = 0; i < n; i++) {
		y += (i == 2) ? 20 : 50;
		x = (x + 170) % 400;
		switch (i) {
			case 0:
				c = "#ff0000";
				break;
			case 1:
			case 4:
				c = "#00ff00";
				break;
			case 3:
				continue;
			default:
				c = "#0000ff";
		}
		for (let a: number = 50; a > 0; a -= 20) {
			placeDiv(c, x, y, a, a);
			if (i == 4)
				break;
		}
	}

	function placeDiv(_color: string, _x: number, _y: number, _width: number, _height: number): void {
		let div: HTMLDivElement = document.createElement("div");
		document.body.appendChild(div);

		//Diese Art der CSS Zuweisung ist nicht schön und sollte vermieden werden.
		//Eine css Datei anzulegen ist deutlich besser aber in diesem Fall nicht optimal,
		//da jedes Objekt einige individuelle Attribute hat.
		//Was sich gruppieren lässt, sollte stattdessen als css Klasse angelegt werden.
		let s: CSSStyleDeclaration = div.style;
		s.border = "thin solid black";
		s.position = "absolute";
		s.backgroundColor = _color;
		s.width = _width + "px";
		s.height = _height + "px";
		s.left = _x + "px";
		s.top = _y + "px";
	}
}
```