# setWidth(value) #

## Description ##

This method sets the column width.  In order to use this method, you must first get the column object using [getColumn](getColumn.md).

## Arguments ##

The value is expected to be a string containing the value.

## Return Value ##

The column object modified is returned.

## Example ##
```
doc = odslib.ODS()
col = doc.content.getColumn(0)
col.setWidth("0.5in")
```