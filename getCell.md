# getCell(column, row) #

## Description ##
This method is used to get the object for a given cell on the default spreadsheet.  The arguments are the column and the row index numbers.  The columns and rows both start at zero, so you will need to take that into account when trying to figure out which column and row to use.

If you were trying to address cell B4, you would need to know which letter place in the alphabet B occupies.  B is the second place or 1 (A is 0).   You would also need to subtract one from the number of the row since we start at zero.  This means that 4 gives us 3 as the value to use.  B4 would then be called using getCell(1, 3).

Once you have this cell object, you can set values and cell properties.  Each of the methods in this Table Cells section return the cell object, so you can daisy chain them together for convenience.

To start setting values, take a look at [stringValue](stringValue.md) and [floatValue](floatValue.md).  If you want to get cells from another spreadsheet, consider taking a look at [getSheet](getSheet.md).

## Arguments ##

Two integer values are passed to getCell.  The first is the column index and the second is the row index.

## Return Value ##

The cell object at the specified location is returned.

## Example ##
```
doc = odslib.ODS()
cell = doc.content.getCell(1, 3)
```