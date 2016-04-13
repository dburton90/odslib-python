# getRow(index) #

## Description ##

This method gets the row object for the row at a given index from the default sheet.  To get the row from a different sheet, consider using [getSheet](getSheet.md).  The most common reason to get the row is to then set the height of the row using the [setHeight](setHeight.md) method.

## Arguments ##

The value is expected to be an integer.

## Return Value ##

The row object at the given index is returned.

## Example ##
```
doc = odslib.ODS()
row = doc.content.getRow(0)
```