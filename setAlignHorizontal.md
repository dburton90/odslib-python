# setAlignHorizontal(value) #

## Description ##

This method sets the horizontal alignment of text within a cell.

## Arguments ##

The following values are acceptable: right, left, center, justify

## Return Value ##

The cell object at the specified location is returned.

## Example ##
```
doc = odslib.ODS()
cell = doc.content.getCell(1, 3)
cell.setAlignHorizontal("right")
```