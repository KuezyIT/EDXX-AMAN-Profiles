# Willkommen!
In diesem Github-Repository findest du eine Sammlung an selbst erstellen AMAN Profile für das EuroScope AMAN Plugin. Alle Profile, die hier zur Verfügung stehen, wurden von mir erstellt und auch getestet.

Es kann durchaus vorkommen, dass es an der ein oder anderen Stelle ein paar Bugs/Fehler gibt. In diesem Fall bitte ich um die Weiterleitung des Bugs. Erstellt dazu einfach im Issues Tab einen neuen Beitrag und gebt mir ein paar Details zum gefundenen Bug.

## Voraussetzungen
Damit ihr die Profile auch nutzen könnt, ist das AMAN Plugin Voraussetzung. Dies könnt ihr hier herunterladen:
* https://github.com/EvenAR/euroscope-aman

## Installation
Das AMAN Plugin könnt ihr ganz einfach in den NAV-Data Plugin Ordner eurer FIR installieren. Laded das Plugin anschließend in EuroScope.

Wichtig dabei ist, dass ihr pro Airport eventuell einen eigenen Ordner erstellt, in dem ihr dann das Profil installiert. Dabei müsst ihr achten, dass die config **immer** `aman-config.json` heißt. Das aktive Profil zieht ihr in den gleichen Ordner, in dem sich das Aman Plugin (DLL Datei) befindet.

Am besten ist es, wenn ihr einfach einen Ordner, mit dem ICAO Code des Airports erstellt, und das jeweilige Profil dort hinterlegt. Bei Bedarf könnt ihr das Profil dann kopieren und dort einfügen, wo sich das AMAN Plugin befindet.

## Nutzung
In AMAN könnt ihr rechts oben auf »Menu« klicken. Dort könnt ihr dann die aktiven Runways auswählen. Sobald ihr eine Runway gewählt habt, wird euch im AMAN direkt eine Timeline angezeigt. Es können auch mehrere Bahnen gleichzeitig aktiv sein, bei mehreren aktiven Runways, wird rechts eine weitere Timeline (pro Runway eine Timeline) angezeigt.

Sofern ein Runway ausgewählt wurde, seht ihr links oben die sogenannten **targetFixes**. Jedes Flugzeug, welches einer dieser Fixes überfliegt, wird angezeigt.

## Hinweis
Laut Profil öffnet sich der AMAN nicht automatisch beim Start von EuroScope. Es kann durchaus sein, dass ihr das Plugin nicht benötigt, weswegen es oftmals nervig sein kann, wenn man das Plugin per Befehl schließen oder wegziehen muss.

Jedes Profil ist konfiguriert, nur Flugzeuge mit der Destination welches im Profil hinterlegt ist, anzuzeigen. Sofern Flugzeuge diverten, muss die Destination angepasst werden, damit das Flugzeug in der Timeline angezeigt wird.

Wenn ihr AMAN öffnen möchtet, gebt den Befehl `.aman open` in EuroScope ein, und ein AMAN Fenster öffnet sich. Dort könnt ihr ganz einfach das Profil laden. Um AMAN wieder zu schließen, nutzt den Befehl `.aman close`