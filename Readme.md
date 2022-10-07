## SIMPLE PRACTICE WITH CSS GRID
A simple responsive css practice without any framework, just using css grid and media queries, using:
* `display: grid;`: To create the cells we will need..
* `repeat:` This allows us to make a loop in the style of javascript or any other programming language.
* `auto-fit:` This reserved word does not allow to autocomplete an element within some columns or a grid in the spaces that are necessary.
* `minmax:` This reserved word allows us to define the size of the rules as a minimum of `15rem` and a maximum of `1fr`;
* `grid-template-columns: repeat(auto-fit, minmax(15rem,1fr));` This allows us to create the columns we wanted.
* `grid-template-columns: repeat(12, 1fr);`: It allows us to create the columns of the grids, the first data being the number of columns that we want the element to have, and the second data being the space that we want the columns to have, in this case a fraction of the total element.
* `grid-template-rows: repeat(12, .40fr);`: Like the previous command, this one allows us to create rows instead of columns.
* `grid-gap: 20px;`: This command allows us to give an internal spacing between the elements, but not the lateral ones.
* `grid-column: span 10;`: This command allows us to size the columns, you can also put `grid-column-end` or `grid-column-start` to size the start and end of the columns.
* `span:` This command allows us to merge multiple columns or rows. giving it a number that would be the spaces we want to merge.
* `grid-row: 2/12;`: It happens similarly to `grid-column` except this command resizes the rows, and the data `2/12` means it will start at row 2 through row 12.

## TO END
* Tests performed on Brave and Opera browsers.
