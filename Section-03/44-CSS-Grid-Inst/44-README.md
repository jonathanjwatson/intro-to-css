# CSS Grid

In order to style elements in a responsive manner, CSS introduced a Grid concept. 

Each row has 12 columns of width available. 

Elements are sized depending on how many column widths they take up. 

While an element take take 1-12 column widths, they cannot take *more* than 12 column widths. 

If a row has more than 12 column widths of elements, the elements rollover to the next row. 

![12 Columns](./assets/12-columns.gif)

Fortunately, Bootstrap has adopted this system to allow us to quickly build responsive layouts. 

## Todo:

1. Build a basic HTML page from scratch. 
2. Import Bootstrap
3. Build a page that contains a full-width heading.
4. Add a section where 1/2 is an image and 1/2 is text. 
5. Add a section with three columns of text. 

## Note:

1. For `.col` classes to work, you *must* have `.container` and `.row` classes above it in three DOM tree. 

## Questions:
1. How could we make this even most responsive? 
2. Is there a ways to further customize how many columns an element will take up?