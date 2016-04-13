# setFontColor(value) #

## Description ##

This method sets the color of the text in a cell.

## Arguments ##

The value must be the standard hash with hex HTML style numbers.

## Return Value ##

The cell object at the specified location is returned.

## Example ##
```
doc = odslib.ODS()
cell = doc.content.getCell(1, 3)
cell.setFontColor("#ff0000")
```