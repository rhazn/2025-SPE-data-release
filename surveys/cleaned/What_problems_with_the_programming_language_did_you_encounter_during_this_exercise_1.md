# What problems with the programming language did you encounter during this exercise?

## Jayvee

When using jayvee, I set up the pipline but can't get a valid database. I know the problem is with the tableinterpreter but I don't know which column has the wrong data type, but then I saw the tutor on the forum and said that you can use jv<file> -d check, I successfully found the problem and solved it

the pipeline did not do the thing is expected and the error messages where bad but with the -d flag i got the explanations i needed, so i could fix it

The Documentation was very short of examples and debugging is difficult

Can't access online data.

can not rename the first row (range only seems to work for columns, not for rows)
no support for advances data types (geodaten was a cell with two comma separated decimals) 

I have a problem with the datatype of one column which could be a tuple or list or just an object. I couldn't find what datatypes does the jayvee support for the columns. I just used text and i am not sure if that is the right option, but it seemed to work fine and it appeared correctly in the database.

What I faced, I have created issue already.

To understand the syntax of new language 

understanding how pipeline in Jv works and giving data types to column

In der Dokumentation des TableInterpreters sind die Beispiele anders, als in den Folien -> [columnname] typed / oftype [type]
Ich habe erst nur in die Onlinedokumentation geschaut und mich gewundert warum ich einen Fehler angezeigt bekommen. Ich weiß nicht ob das vielleicht eine Versionssache ist, also das es sich mit der Zeit geändert hat (ich habe version 0.0.15 verwendet), dann bitte bei der Onlinedokumentation mit angeben auf welche Version der Sprache es sich bezieht

## Python

I got problems with the automatic feedback:  Can not find expected output file: airports.sqlite. Make sure your model generates it correctly!

Maybe it was because I used unallowed libraries

Since I am not too familiar with Python, I ran into some general problems with the programming environment and just generally figuring things out

lack of familiarity with using github!

Some more examples in this would have been helpful.
Difficulties while checking exercise feedback

Renaming the columns for better speaking names was not possible due to the given tests failing after trying that.

Python version and virtual env. Getting a specific Python version to run on my local machine is always tedious.

I don't like reading documentation

Keine Probleme mit der Programmiersprache, aber falls ihr Feedback zur Aufgabenstellung wollt:
In der Aufgabenstellung heißt es, es soll der beste Datentyp ausgewählt werden für jede Spalte. Dies sollte bessere ausgedrückt werden, ob es sich hier um eine manuelle Aufgabe handeln sollte (die Daten einzeln durchgehen und den Datentyp ändern z.B. Integer anfangen und ggf. auf BIGINT updaten falls ein größerer Wert existiert) oder ob  - besonders weil man ja eigentlich über eine automatische Datenpipeline redet - dies während der Laufzeit passieren soll.

Das programmieren der Aufgabe war nach der ersten Projektaufgabe sehr einfach und hätte nach meinen Erwartungen nur 20 Minuten gedauert. Ich musst bloß sehr viel Zeit investieren weil ich nicht mehr in der Lage war sqlite Dateien mit dem Befehl DataFrame.to_sql zu öffnen. Die Lösung dafür war das der angegebene Pfad aus einem anderen Startordner ausging. 