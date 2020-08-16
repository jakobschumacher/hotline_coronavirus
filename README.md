# Hotline Coronavirus
Mini-Software zur Datenaufnahme und Bearbeitung von Covid-Fällen und Kontaktpersonen. Eine Excel-Tabelle zur Datenerfassung und eine SurvNet Vorlage mit einem Abstrichscore.  

## Prinzip und Arbeitsweise der Excel-Tabelle
Die Mini-Software soll die Arbeit für die Gesundheitsämter zur Eindämmung des Coronavirus unterstützen. Mit ihrer Hilfe sollen Hotline-Mitarbeitende innerhalb eines Telefonanrufs alle zu bearbeitenden Dinge erledigen können. Das Prinzip ist der "One-Stop-Shop": Während man mit der Person telefoniert werden die Daten aufgenommen, dann können mit den Buttons alle Dinge erledigt werden, die man typischerweise erledigen muss und am Ende des Telefonanrufs ist die Arbeit für diese Fall beendet. 

## Prinzip und Arbeitsweise des Abstrich Score
Bei einem Person für die ein Abstrich evaluiert werden soll werden bestimmte Risikofaktoren erfasst. Für jeden Risikofaktor gibt es einen Punktwert. Alle Punktwerte werden zusammengezählt. Überschreitet der zusammengezählte Wert einen aktuell festgelegten Grenzwert wird ein Abstrich initiiert. Die Höhe des Grenzwertes wird festgelegt anhand der Abstrichkapazität.

## Voraussetzungen für die Excel-Tabelle
* Excel 2016
* Outlook 2016. (Eine Benutzung ist auch möglich mit Groupwise, dazu müsste die Excel-Tabelle aber angepasst werden.)

## Voraussetzungen für den Abstrich Score
* SurvNet

## Installation
Download der Excel-Tabelle. Die Tabelle ist mit selbergeschreibenen Makros versehen. 
In der Tabelle müssen die jeweiligen Pfade angepasst werden. Diese Pfade sind teilweise im VBA Code, teilweise im Tabellenblatt "Einstellung". Die Datei ist eine Vorlage, die in einem Ordner abgelegt werden kann. Jede Person öffnet also eine neue Instanz der Excel-Datei und speichert diese über eine spezielle Funktion in einem Ordner ab. 
Download der SurvNet-Vorlage. Platzierung der Word-Vorlage in SurvNet Vorlagen Ordner. 

## Sicherheit
Diese Mini-Software ist bestenfalls im Alpha-Stadium und nicht von entsprechenden Sicherheitsexperten überprüft. Die selbstgeschriebenen Makros können fehlerhaft sein und zu Abstürzen, Datenverlust oder ähnlichem führen. Möglicherweise kann es zu anderen Sicherheitsproblemen kommen, die wir nicht erahnen. 

## Entwicklung
Die Excel-Tabelle  befindet sich nicht mehr in aktiver Entwicklung. Weiterentwickelte Software wird in anderen Gesundheitsämtern eingesetzt. Eine Mitarbeit ist gerne gewünscht. 



