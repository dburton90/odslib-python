# getSheet(index) #

## Description ##

This method gets the sheet at a given index and also sets it to be the default sheet for all future [getCell](getCell.md), [getRow](getRow.md), and [getColumn](getColumn.md) requests.

## Arguments ##

The value is expected to be an integer.

## Return Value ##

The sheet object is returned.

## Example ##
```
doc = odslib.ODS()
doc.content.getSheet(0)
```