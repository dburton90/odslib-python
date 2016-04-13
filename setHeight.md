# setHeight(value) #

## Description ##

This method sets the row height.  In order to use this method, you must first get the row object using [getRow](getRow.md).

## Arguments ##

The value is expected to be a string containing the value.

## Return Value ##

The row object modified is returned.

## Example ##
```
doc = odslib.ODS()
row = doc.content.getRow(0)
row.setHeight("0.5in")
```