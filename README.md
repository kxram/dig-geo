# <a name='projektstruktur'>Projektstruktur: Das wichtigste</a>

- Im Ordner **\_pages** befinden sich die statischen Seiten (die auch in der Navigationsleiste anwählbar sind).
- Im Ordner **\_posts** befinden sich Ankündigungen und Berichte. Um einen neuen Post zu verfassen sollte auch das Format des Dateinamens (YYY-MM-DD-titel-mit-bindestrichen.md) eingehalten werden.
- Bilder können in den Ordner **bilder** hochgeladen und in den Texten verlinkt werden.

# Für schnelle kleine Änderungen

1. Einen GitHub Account erstellen / einloggen
1. Im Repository [ktiu/dig-geo][1] die betreffende Datei finden (siehe [Projektstruktur][2])
2. Auf der zu ändernden Datei auf den kleinen Stift im Menü oben rechts klicken:
![Fork this project and edit the file][image-1]
3. Änderungen vornehmen und auf **Propose file change** klicken
4. Überprüfen und **Create pull request** wählen
5. Ggf. eine kurze Beschreibung / Erklärung der Änderungen verfassen und Pull request bestätigen
6. Das war's! Der Pull request mit den Änderungen ist für alle sichtbar und kann angenommen werden.

# Für umfassendere Änderungen...

...(z.B. Designänderungen) ist es besser, zuerst an einer eigenen Kopie des gesamten Projekts Änderungen vorzunehmen und sich anzeigen zu lassen. Das geht so:

1. Im Repository [ktiu/dig-geo][3] auf "Fork" klicken. Das kopiert das komplette Projekt in den eigenen Account. (Das passiert übrigens auch bei der schnellen Methode automatisch im Hintergrund.)
1. Die Datei "CNAME" im eingenen Repository löschen (sonst kommt GitHub bei der Vorschau durcheinander).
1. Im *eigenen* Repository (also https://github.com/{eigener-benutzername}/dig-geo) auf "Settings" klicken
2. Im Menüpunkt **GitHub Pages** die Option **Source** auf »master« setzen. Damit werden die Änderungen, die im eigenen Repository vorgenommen werden, live (mit einer kleinen Verzögerung) angezeigt.
3. Die Adresse für die Vorschau lautet: https://{eigener-benutzername}.github.io/dig-geo/
	- Der Markdown-Editor [Prose][4] kann hierbei helfen.
	- Die Profi-Variante ist dann, sich den [GitHub Desktop][5] (oder sogar nur Git) und [Jekyll][6] zu installieren, das Repository lokal zu ›klonen‹ und sich die Änderungen in Echtzeit auf localhost anzeigen zu lassen.
4. Wenn die eigene Kopie soweit ist, dass die Änderungen in die Live-Seite einfließen sollen, muss noch ein ›pull request‹ erstellt werden. Hierzu auf **New pull request** klicken (oder diesem [Link](../../compare/ktiu:master...master) folgen)
5. Dann als **base fork** auswählen: »ktiu/dig-geo«
6. Als **head fork**: »{eigener-benutzername}/dig-geo« 
7. Dann prüft GitHub, ob die Versionen zusammengeführt werden können. Solange nicht in der Zwischenzeit die gleichen Zeilen bearbeitet wurden, sollte das gehen.
8. Auf **Create pull request** klicken und dann nochmal bestätigen. Fertig!

Wenn ihr in weiterer Folge Aktualisierungen von ktiu/dig-geo in euren Fork "nachziehen" wollt, könnt ihr den Pull-Request auch in die andere Richtung machen, d.h. »{eigener-benutzername}/dig-geo« als base fork und »ktiu/dig-geo« als head fork. ([Link](../../compare/master...ktiu:master))


# Zum Weiterlesen

- Das Format der Dateien ist Markdown, welches dann automatisch in HTML umgewandelt wird. https://guides.github.com/features/mastering-markdown/
- Die Seite ist auf GitHub gehostet, wofür es hier eine schöne Einleitung gibt: https://guides.github.com/introduction/flow/

[1]:	https://github.com/ktiu/dig-geo
[2]:	#projektstruktur
[3]:	https://github.com/ktiu/dig-geo
[4]:	https://prose.io
[5]:	https://desktop.github.com/
[6]:	https://jekyllrb.com

[image-1]:	https://raw.githubusercontent.com/ktiu/dig-geo/master/bilder/tutorial/fork_and_edit.png
