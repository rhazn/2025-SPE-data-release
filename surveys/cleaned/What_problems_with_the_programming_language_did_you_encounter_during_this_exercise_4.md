# What problems with the programming language did you encounter during this exercise?

## Jayvee

Can we please get a RangeConstraint for integer types as well? It would be handy for validating dates.

One issue was in the docs but it was resolved quickly. But in general it would nice to see a pipeline in the docs which uses the transforms with the block. I looked up in GitHub how it is used because I felt that I needed some more context. 

    constraint ValidDeviceID oftype RangeConstraint {
        lowerBound: 1;
        lowerBoundInclusive: true;
        upperBound: 999;
        upperBoundInclusive: true;
       as: Integer // implement me!
    }
--> Sobald ein RangeConstraint gesetzt wird, wird der Wert als Dezimal gesehen. Dies finde ich unschön, es sollte es Möglichkeit geben den Typ "decimal" oder "integer" auszuwählen, anstatt einfach immer decimal zu nehmen, weil so letztlich auch keine sinnvoll Validierung möglich ist (nur vollständige Werte)
---------------------------
    block ZipArchiveInterpreter oftype ArchiveInterpreter {
    archiveType: "zip";
}


block TemperaturesFilePicker oftype FilePicker {
  path: "/data.csv";
}

Das Nutzen dieser Kombination gehört definitiv in die Dokumentation, ich fand es nicht gerade selbsterklärend anhand der Dokumentation.
--------------
- Die simple Transformation von decimal zu integer ist viel zu umständlich meiner Meinung nach


lack of enough jayvee documentation available online. I know its very new and still developing and that is one of the cons!

Es war etwas umständlich die Columns umzubenennen wie es in der Aufgabenstellung gefordert war. Evtl. würde hier eine weitere API -Funktion mehr Komfort schaffen :)

The code was not highlighted correctly in VSCode with some functions (as if they do not exist)

## Python

Beim zip file richtig extrahieren, welche Methode am besten verwendet wird und welche Daten man validieren kann/soll.

Die Dokumentation der read_csv-Methode in pandas enthält keine gute Beschreibung, wie man nur die ersten Spalten jeder Zeile einliest. 

when reading in the data, pandas really wanted to create a MultiIndex and it was had to prevent it from doing so...

exercise feedback for shape returns invalid even if columns shape is 7 (as it should)