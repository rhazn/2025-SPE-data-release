# What language features or libraries would have made solving the exercise easier?

## Jayvee

Das man beim Cell Writer mehrere Spalten auf einmal ändern kann 

It would be quite handy if there was a way to apply a transform to multiple columns or a range of columns at once, instead of being limited to only one column.

tbh after I had the solution I was impressed how easy the pipeline is and how straightforward transforming values are.

    block CelsiusToFahrenheitTransformer_Batterie oftype TableTransformer {
    inputColumn: 'Batterietemperatur';
    outputColumn: 'Batterietemperatur';
    use: CelsiusToFahrenheit;
    remove: True // implement me!
    }
- Mittels remove soll entschieden werden können, ob die inputColumn entfernt werden soll nach der Transformation
-------------------------------------------
    block TemperaturesTableInterpreter oftype TableInterpreter {
        header: true;
        columns: [
            "Geraet"  oftype DeviceID,
            "Temperatur in ..." --> "Temperatur" oftype decimal,
            "Hersteller" oftype text,
             ....
        ];
    }
- Über den TableInterpreter sollte es möglich sein die Spaltennamen zu ändern mittels  currentName --> newName oftype decimal.
Ob header true oder false ist dürfte egal sein bei der Implementierung des features 
-------------------
- deleteColumn mit input und output type Table

It would be nice to have default blocks, for example: I use the  TextFileInterpreter without any arguments but still have to define it and cant use TextFileInterpreter in the pipeline without writing a block for it.  

## Python

Normal libs