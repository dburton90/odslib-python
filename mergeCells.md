# mergeCells(column, row, colspan, rowspan) #

## Description ##

This method takes the cell at a column and row location and causes it to span multiple cells.  All of the cells that get covered will still be there and will still be able to have values, but they will become hidden.

## Arguments ##

There are four arguments.  The column and row are the index values of the cell to be spanned.  The colspan integer value is the number of cells wide the cell grows to cover.  The rowspan integer value is the number of cells high the merged cell will occupy.  The colspan and rowspan values should each be at least 1 in value.

## Return Value ##

The cell object that is merged is returned, even though this method is not called from the cell object.

## Example ##
```
doc = odslib.ODS()
cell = doc.content.mergeCells(0, 0, 4, 1)
```