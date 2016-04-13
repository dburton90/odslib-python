# setAlignVertical(value) #

## Description ##

This method sets the vertical alignment of text within a cell.

## Arguments ##

The following values are acceptable: top, bottom, middle, center

## Return Value ##

The cell object at the specified location is returned.

## Example ##
```
doc = odslib.ODS()
cell = doc.content.getCell(1, 3)
cell.setAlignVertical("top")
```