# makeSheet(value) #

## Description ##

This method creates a new sheet with the given name.  The default sheet is then set to the newly created sheet.  If you want to go back to a previous sheet, you can use the [getSheet](getSheet.md) method.  If you want to create a lot of different sheets, you can use the [getSheetIndex](getSheetIndex.md) method to help you keep track.

## Arguments ##

The value is expected to be string for the sheet name.

## Return Value ##

The sheet object is returned.

## Example ##
```
doc = odslib.ODS()
doc.content.makeSheet("Sheet2")
```