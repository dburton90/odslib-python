# setHidden(boolean) #

## Description ##

This method sets the visibility of a row or column object.  To get these objects, you must use either [getRow](getRow.md) or [getColumn](getColumn.md) first.

## Arguments ##

The value is expected to be a boolean value.  True to hide the row or column and False to make it visible.  All rows and columns are visible be default, to the setHidden(False) is not really needed.

## Return Value ##

The row or column object modified is returned.

## Example ##
```
doc = odslib.ODS()
col = doc.content.getColumn(1)
row = doc.content.getRow(2)
col.setHidden(True)
row.setHidden(True)
```