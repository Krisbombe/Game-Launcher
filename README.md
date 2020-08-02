

Game-Launcher 1.0

1.0|Wie fügt man ein Hotkey hinzu?

1.1 Erstellen sie ein Desktopverknüpfung bei der Plattform des Programms.
1.2 Klicken sie Rechtsklick auf der Verknüpfung und wählen sie "Eigenschaften" an.
1.3 Klicken sie auf den Unterpunkt "Webdokument" und kopieren sie das Feld "URL".
Info| Beispiel-links: Steam:"steam://rungameid/123456";Uplay:"uplay://launch/1234/0";Origin:"";
1.4 Öffnen sie den Installationspfad vom Game-Launcher. Standardpfad:"C:\Users\*Username*\AppData\Roaming\Game-Launcher\"
1.5 Öffnen sie die Datei "ConfigSystem.cfg" mit einem beliebigen Editor.
1.6 Das Config System ist folgendermaßen aufgebaut:

"hotkey.1"="*Eingabe*"		|Hier fügen sie das kopierte Feld "URL" von Schritt 1.3 ein.
"hotkey.name1"="*Eingabe*"	|Hier geben sie zu dem entsprechenden Hotkey den passenden Anzeigenamen an.

1.7 Die Hotkey verteilung sieht wie folgt aus:
Steam Hotkeys: 			01-15;
Uplay Hotkeys: 			16-20;
Origin Hotkeys: 		21-25;
Rockstar Games Hotkeys: 26-30;
Battlenet Hotkeys: 		31-35;
Sonstige Hotkeys: 		36-40;

1.8 So können sie sich die hotkeys nach belieben konfigurieren.

Info| Falls das Programm fehlerhaft oder garnicht funktioniert:
"bitte öffnen sie das Troubleshooting was sich im Installationspfad befindet"
