# setItalic(boolean) #

## Description ##

This method turns on and off the italics attribute for the text within a cell.

## Arguments ##

The value must be either True or False

## Return Value ##

The cell object at the specified location is returned.

## Example ##
```
doc = odslib.ODS()
cell = doc.content.getCell(1, 3)
cell.setItalic(True)
```