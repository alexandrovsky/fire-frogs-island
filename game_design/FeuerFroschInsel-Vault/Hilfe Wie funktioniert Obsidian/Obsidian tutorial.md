---
modified: 2026-10-22T12:22:19+02:00
---
## Wichtige hotkeys
- Command Palette: cmd+p
- Datei öffnen: cmd+o
>[!tip]
>Die Suchfunktion ist sehr gut, wenn man irgendeine Buchstabenkombination die in dem Dateinamen enthalten ist sucht wird man sie finden
- Insert Template to current file: ctrl+i
- switch Tabs: ctrl+tab

## Formatierung
- Text wird in [Markdown](https://markdownformatting.com/cheat-sheet) geschrieben
- Obsidian hat noch einige andere Funktionen, wie z.B. Callout boxen die man beim googlen meistens schnell findet
- Links zwischen files im Vault werden durch doppelte eckige Klammern erstellt
	- Wenn man die Verlinkung anders nennen möchte als die verlinkte Datei Schreibt man in die eckigen Klammern zuerst den Namen der verlinkten Datei und dahinter durch einen | getrennt den angezeigten Text
		- Wenn man eine andere Schreibweise häufig verwendet (z.B. Genitivformulierungen) kann man diese in der Datei als Alias hinzufügen und dann die Datei auch über den Alias verlinken
- Wenn an irgendeiner stelle etwas ist was ihr rekreieren wollt kann man mit dem cursor an die entsprechende Stelle navigieren und in der Regel so die Schreibweise sehen. Wenn das nicht möglich ist, ist oben rechts des Blocks ein Symbol auf das man klicken kann um sich die Schreibweise anzusehen
### Frontmatter
- wenn man ganz oben an einem Dokument drei "-" hintereinander schreibt erscheinen Dokumenten Properties
- Mit Properties kann man wichtige Inhalte der Dokumente schnell einsehbar machen und Dateien organisieren
- Es gibt verschiedene Arten von Properties, die durch Rechtsklick auf das Symbol am Anfang der Zeile ausgewählt werden können. Schaut da gerne immer was ihr für verschiedene Infos für Sinnvoll haltet, in Meiner Erfahrung sind Listen meist die Hilfreichsten Properties
	- Die Auswahl lässt sich im Nachhinein noch ändern
- Bei dem Erstellen von neuen Properties (Falls ihr zum Beispiel eintragen wollt was ihr gegessen habt während ihr die Notiz bearbeitet) bitte darauf achten, dass der Name keine Leerzeichen enthält. Das mach das Weiterverwerten einfacher


## Plugins
- Falls euch irgendeine Funktion in Obsidian fehlt gibt es dazu in den meisten Fällen Plugins von der Community, die ihr in den Einstellungen finden und installieren könnt
	- Falls ihr ein Plugin installiert, welches eine neue Art von Dateien erstellen kann sprecht das am besten mit Dimi ab, damit Github damit keine Probleme bekommt
- Falls Fragen zur Funktionsweise oder Syntax von einzelnen Plugins aufkommen kann man das entweder googlen oder in den Einstellungen unter Optionen zu Externe Plugins und weiter zum entsprechenden Plugin navigieren (nicht die Auflistung der Plugins die sich in der Sidebar der Einstellungen findet, sondern die Schaltfläche in der Optionen Kategorie, wo man auch Plugins installieren kann). Dort findet man auch häufig wertvolle Informationen

### Metabind
- Sorgt dafür dass wir Frontmatter hinzufügen und formatieren können

### Dataview
- Kann Dateien nach ihren Properties filtern und entsprechende Listen oder Tabellen erstellen und in Echtzeit updaten
- Für Syntax schaut wie oben; **Ich bitte darauf zu verzichten mit dem Operateor "FROM" nach Frontmatter zu filtern**, weil das immer wieder zu Problemen führt. Die funktionierende Syntax für z.B. eine Liste ist:
	- LIST WHERE contains(art der Property(z.B. type), "Inhalt der Property(z.B. NPC))
	- Durch Verknüpfung mit AND lässt sich so beliebig spezifisch filtern