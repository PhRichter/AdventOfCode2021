### Konzepte

Alle Ideen und Lösungskonzepte der einzelnen [Rätsel](https://adventofcode.com/2021) auf einem Blick.
<ul>
  <li>Tag 01: </li>
  <li>Tag 02: </li>
  <li>Tag 03: </li>
  <li>Tag 04: </li>
  <li>Tag 05: </li>
  <li>Tag 06: </li>
  <li>Tag 07: </li>
  <li>Tag 08: </li>
  <li>Tag 09: Rekursion</li>
  <li>Tag 10: Es soll überprüft werden, ob alle geöffneten Klammern auch wieder geschlossen werden. Es kann immer nur die letzte geöffnete Klammer geschlossen werden, daher ist nur unmittelbar diese Klammer für die Betrachtung relevant. Hier bietet sich ein Stack an, welchen ich als String realisiert habe. Die einzigen verändernden Operationen sind das Hinzufügen eines Elements ans Ende des Strings und das Löschen des letzten Elements (ausgeführt als Kopieren des gesamten Strings mit Ausnahme des letzten Elementes und Überschreiben des aktuellen Strings). Wenn eine Klammersequenz fehlerhaft ist, passen die schließende Klammer und das aktuelle Element des Stacks nicht zusammen. Ist eine Sequenz unvollständig, bleiben am Ende Elemente im Stack zurück. </li>
  <li>Tag 11: Wieder Rekursion</li>
  <li>Tag 12: Wegfindungsalgorithmus</li>
  <li>Tag 13: </li>
  <li>Tag 14: </li>
  <li>Tag 15: Dijkstra</li>
  <li>Tag 16: Parser</li>
  <li>Tag 17: In Teil 1 ist v_x irrelevant. Die kann beliebig sein mit der Einschränkung, dass v_x=0 über dem Zielgebiet sein muss. Am höchsten Punkt gilt v_y=0 und dann ist an jeder y-Position die Geschwindigkeit nach oben v_y und nach unten -v_y. Die Eintrittstiefe wird also nur von v_y_init bestimmt und wird auf die maximale Tiefe des Zielgebiets gesetzt. Daraus kann die maximale Höhe berechnet werden. Für Teil 2 werden alle möglichen v_x_init berechnet und wie viele Schritte gegangen werden können. Danach bestimme die möglichen v_y_init, mit denen das Zielgebiet erreicht wird<\li>
</ul>
