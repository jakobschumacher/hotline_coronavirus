# Hotline Coronavirus
Mini-Software zur Datenaufnahme und Bearbeitung von Covid-Fällen und Kontaktpersonen. Eine Excel-Tabelle zur Datenerfassung und eine SurvNet Vorlage mit einem Abstrichscore.  

# Abstrichscore

## Prinzip und Arbeitsweise
Bei einem Person, für die ein Abstrich evaluiert werden soll, werden bestimmte Risikofaktoren erfasst. Für jeden Risikofaktor gibt es einen Punktwert. Alle Punktwerte werden zusammengezählt. Überschreitet der zusammengezählte Wert einen aktuell festgelegten Grenzwert, wird ein Abstrich initiiert. Die Höhe des Grenzwertes wird festgelegt anhand der Abstrichkapazität. In diesem Repository ist ein ausdruckbares Dokument hinterlegt (Manueller Abstrichscore) und eine Survnet-Vorlage.

## Installation
- Manueller Abstrichscore: Download des [Word-Dokuments](Abstrichscore_manuell.docx) oder des [PDF-Dokuments](Abstrichscore_manuell.pdf). 
- SurvNet-Vorlage: Download der [SurvNet-Vorlage](https://github.com/jakobschumacher/hotline_coronavirus/blob/master/Covid%20-%20Abstrichscore%20-%20Vorstellung.dotm). Vorsicht, diese ist eine Word-Datei mit Makros, ein Download ist möglicherweise von den Sicherheitseinstellungen untersagt. Platzierung der Word-Vorlage in SurvNet Vorlagen Ordner. Zusätzlich muss die Datei [ScoreIndex](https://github.com/jakobschumacher/hotline_coronavirus/blob/master/ScoreIndex.txt) im Vorlagen Ordner gespeichert werden. Diese enthält den aktuellen Score-Wert.

## Voraussetzungen
* SurvNet

# Spezialisiertes Excel-Tool zur Fall und Kontaktpersonenaufnahme

## Prinzip und Arbeitsweise
Die Mini-Software soll die Arbeit für die Gesundheitsämter zur Eindämmung des Coronavirus unterstützen. Mit ihrer Hilfe sollen Hotline-Mitarbeitende innerhalb eines Telefonanrufs alle zu bearbeitenden Dinge erledigen können. Das Prinzip ist der "One-Stop-Shop": Während man mit der Person telefoniert werden die Daten aufgenommen, dann können mit den Buttons alle Dinge erledigt werden, die man typischerweise erledigen muss und am Ende des Telefonanrufs ist die Arbeit für diese Fall beendet. 

## Voraussetzungen
* Excel 2016
* Outlook 2016. (Eine Benutzung ist auch möglich mit Groupwise, dazu müsste die Excel-Tabelle aber angepasst werden.)

## Installation
Download der Excel-Tabelle. Die Tabelle ist mit selbergeschreibenen Makros versehen. 
In der Tabelle müssen die jeweiligen Pfade angepasst werden. Diese Pfade sind teilweise im VBA Code, teilweise im Tabellenblatt "Einstellung". Die Datei ist eine Vorlage, die in einem Ordner abgelegt werden kann. Jede Person öffnet also eine neue Instanz der Excel-Datei und speichert diese über eine spezielle Funktion in einem Ordner ab. 


# Sicherheit
Diese Mini-Software ist bestenfalls im Alpha-Stadium und nicht von entsprechenden Sicherheitsexperten überprüft. Die selbstgeschriebenen Makros können fehlerhaft sein und zu Abstürzen, Datenverlust oder ähnlichem führen. Möglicherweise kann es zu anderen Sicherheitsproblemen kommen, die wir nicht erahnen. 

## Entwicklung
Der Abstrichscore wird regelmäßig weiter entwickelt. Die Excel-Tabelle  befindet sich nicht mehr in aktiver Entwicklung. Weiterentwickelte Software wird in anderen Gesundheitsämtern eingesetzt. Eine Mitarbeit ist gerne gewünscht. 



