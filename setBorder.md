# setBorder(boolean) #

## Description ##

This method turns on and off the border for the cell.  This method assumes pre-configured values for the border width, color, and style.  If you want to change any of these, you can use the methods [setBorderWidth](setBorderWidth.md), [setBorderColor](setBorderColor.md), and [setBorderStyle](setBorderStyle.md).

## Arguments ##

The value must be either True or False

## Return Value ##

The cell object at the specified location is returned.

## Example ##
```
doc = odslib.ODS()
cell = doc.content.getCell(1, 3)
cell.setBorder(True)
```