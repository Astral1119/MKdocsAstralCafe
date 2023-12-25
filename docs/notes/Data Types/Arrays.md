---
dg-publish:
---
Arrays are any m by n grid of contiguous values where m is the number of rows and n is the number of columns in the array. Within an array, one can have any other kind of data type, including multiple different types. You can also think of arrays as a collection of cells arranged into a rectangle.

All rows of an array must share the same number of columns, and all columns must share the same number of rows.

Arrays can be separated into two types: ranges and virtual arrays. Ranges are referenced directly from the spreadsheet, while virtual arrays are not. Ranges therefore carry additional data, such as the row or column they were sourced from. It is important to make this distinction as some formulae, such as SUMIF, require ranges.