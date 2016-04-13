# About odslib-python #

The odslib-python project is directed at addressing a few issues.  First and foremost, I want to have a library I am comfortable using anytime I want to generate spreadsheets.  There are many things that the odslib-python project is not, so I wanted to list abilities I want it to have along with features I do not want to have.

# Features #

This is a list of features that I would like to see in the odslib-python project.  Some of the features are already present and some are on my TODO list.

  * Create ODS spreadsheet documents which can be read by LibreOffice
  * Ability to work with multiple sheets in a spreadsheet file
  * Ability to put numeric and string values into the spreadsheets
  * Ability to adjust column and row width, height, and visibility
  * Ability to apply bold, italics, and underline
  * Ability to adjust fonts and font sizes
  * Ability to adjust text alignment and rotation/orientation
  * Ability to span multiple cells
  * Ability to apply various number formats
  * Ability to change the background and foreground colors in a cell
  * Ability to adjust border colors and visibility
  * Ability to insert formulas into cells for external calculation
  * Ability to set meta data name, subject, description, and author

# Not Features #

This is a list of the things that I do not expect I will ever implement in odslib-python.

  * Will not create documents other than ODS
  * Will not calculate formula values (LibreOffice does that)
  * Will not read and parse ODS files to allow editing
  * Will not convert to or from other file formats (ie. docx)