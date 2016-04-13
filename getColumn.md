# getColumn(index) #

## Description ##

This method gets the column object for the column at a given index from the default sheet.  To get the column from a different sheet, consider using [getSheet](getSheet.md).  The most common reason to get the column is to then set the width using the [setWidth](setWidth.md) method.

## Arguments ##

The value is expected to be an integer.

## Return Value ##

The column object at the given index is returned.

## Example ##
```
doc = odslib.ODS()
col = doc.content.getColumn(0)
```