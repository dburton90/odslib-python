# setBorderColor(value) #

## Description ##

This method sets the color of a cells border.  In addition to setting the border, this method assumes you want to see the border and activates the border.  To inactivate the border you can use the [setBorder](setBorder.md) method.

## Arguments ##

The value must be the standard hash with hex HTML style numbers.

## Return Value ##

The cell object at the specified location is returned.

## Example ##
```
doc = odslib.ODS()
cell = doc.content.getCell(1, 3)
cell.setBorderColor("#ff0000")
```