# floatValue(value) #

## Description ##

This method assigns a value to a given cell.

## Arguments ##

The value is expected to be a number.

## Return Value ##

The cell object at the specified location is returned.

## Example ##
```
doc = odslib.ODS()
cell = doc.content.getCell(1, 3)
cell.floatValue(10)
```