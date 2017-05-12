# <a name='projektstruktur'>Projektstruktur: Das wichtigste</a>

- Im Ordner *_pages* befinden sich die statischen Seiten (die auch in der Navigationsleiste anwählbar sind).
- Im Ordner *_posts* befinden sich Ankündigungen und Berichte. Um einen neuen Post zu verfassen sollte auch das Format des Dateinamens (YYY-MM-DD-titel-mit-bindestrichen.md) eingehalten werden.
- Bilder können in den Ordner *bilder* hochgeladen und in den Texten verlinkt werden.

# Für schnelle kleine Änderungen

1. Einen GitHub Account erstellen / einloggen
1. Im Repository [ktiu/dig-geo](https://github.com/ktiu/dig-geo) die betreffende Datei finden (siehe [Projektstruktur](#projektstruktur))
2. Auf der zu ändernden Datei auf den kleinen Stift im Menü oben rechts klicken:
![Fork this project and edit the file](https://raw.githubusercontent.com/ktiu/dig-geo/master/bilder/tutorial/fork_and_edit.png)
3. Änderungen vornehmen und auf *Propose file change* klicken
4. Überprüfen und *Create pull request* wählen
5. Ggf. eine kurze Beschreibung / Erklärung der Änderungen verfassen und Pull request bestätigen
6. Das wars! Der Pull request mit den Änderungen ist für alle sichtbar und kann angenommen werden.

# Für umfassendere Änderungen...

...(z.B. Designänderungen) ist es besser, zuerst an einer eigenen Kopie des gesamten Projekts Änderungen vorzunehmen und sich anzeigen zu lassen. Das geht so:

1. Im Repository [ktiu/dig-geo](https://github.com/ktiu/dig-geo) auf "Fork" klicken. Das kopiert das komplette Projekt in den eigenen Account. (Das passiert übrigens auch bei der schnellen Methode automatisch im Hintergrund.)
1. Im *eigenen* Repository (also https://github.com/*\{eigener-benutzername\}*/dig-geo) auf "Settings" klicken
2. Im Menüpunkt *GitHub Pages* die Option *Source* auf "Master" setzen. Damit werden die Änderungen, die im eigenen Repository vorgenommen werden, live (mit einer kleinen Verzögerung) angezeigt.
3. Die Adresse für die Vorschau lautet https://{eigener-benutzername}.github.io/dig-geo/ 
(Die Profi-Variante ist dann, sich den GitHub Desktop [oder Git] und [Jekyll](https://jekyllrb.com) zu installieren, das Repository lokal zu 'klonen' und sich die Änderungen in Echtzeit lokal anzeigen zu lassen.)
4. Wenn die eigene Kopie soweit ist, dass die Änderungen in die Live-Seite einfließen sollen, muss noch ein Pull-Request erstellt werden.


# Zum Weiterlesen

- Das Format der Dateien ist Markdown, welches dann automatisch in HTML umgewandelt wird. https://guides.github.com/features/mastering-markdown/
- Die Seite ist auf GitHub gehostet, wofür es hier eine schöne Einleitung gibt: https://guides.github.com/introduction/flow/
