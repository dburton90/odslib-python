# setCellColor(value) #

## Description ##

This method sets the background color of a cell.  It does not appect the font color of the text.  To change the font color, you will need to take a look at the [setFontColor](setFontColor.md) method.

## Arguments ##

The value must be the standard hash with hex HTML style numbers.

## Return Value ##

The cell object at the specified location is returned.

## Example ##
```
doc = odslib.ODS()
cell = doc.content.getCell(1, 3)
cell.setCellColor("#ff0000")
```