# What language features or libraries would have made solving the exercise easier?

## Jayvee

If I could do the problem using Python, I could solve it quickly.

There should be a way to rename multiple cells (especially headers) in one step, f.e. input list of indices and list of new values for the update. |indices_list| = |update_values_list|

-> update accordingly, in pandas f.e. this is possible and very useful

If there is a column deleter, it should also work with lists of columns

In the columndeleter block: a range option
In the textfileinterpreter block: docu should specify which encodings are allowed

Being able to select ranges in the ColumDeleter and RowDeleter (even if i didn't used them)
In the text range selector (and also in other blocks) being able to give the "row number from the bottom" like -2 for the second last row

1) die Möglichkeit, (vor)letzte Zeilen zu löschen
2) die Möglichkeit, eine Range von Columns zu löschen

One feature I'd want to see in jayvee is writing at multiple cells in a single block even if they're not in succession
for example:
block CarsRenameCols oftype CellWriter {
        at: [A1, W1, AQ1] ;
        write: ["date", "CIN", "name"];
    }

Eine Range für Spaltenlöschung, die spalten auslässt.

for Jayvee, something like ColumnSelector which uses collection as the property 

## Python