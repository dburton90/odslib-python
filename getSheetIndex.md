# getSheetIndex() #

## Description ##

This method returns the sheet index for the current sheet.  This can be helpful if you are working with a lot of sheets and need to change between sheets multiple times.  You can then use the [getSheet](getSheet.md) method to switch the current sheet.

## Return Value ##

The current sheet index number is returned.

## Example ##
```
doc = odslib.ODS()
index = doc.content.getSheetIndex()
```