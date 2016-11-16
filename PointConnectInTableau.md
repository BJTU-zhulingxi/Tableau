#20161116


## How to connect two point in tableau

### First you make a table like below:
|ID       | POINT       |	X	|Y|COLOR|QUANTITY|
|--------|--------|--|--|--|--|
|1	|A	|1	|2|R|10|
|1|	D|	4|	3|R|10|
|2|	A|	1|	2|G|20|
|2	|E|	2|	2|G|20|
|3|	B	|3	|2|B|18|
|3	|C|1	|7|B|18|
|4|	B|	3	|2|Y|16|
|4	|D	|4	|3|y|16|

That means you have 5 point which named ass A,B,C,D,E.

You have 4 lines which named as 1,2,3,4.

The point with same ID will be connnect as a line.

### How to do LINE chart in Tableau

2. import the data to Tableau
3. Put X on the column 
4. Put Y on the row
5. Change the X to Dimension
6. Change the Y to Dimension
7. Drop the ID to the Mark field

### How to decorate with other field
You can also use other field as color or size of the line.
1. color the line.
So you can use the COLOR filed to color the line,just drag and drop the COLOR field to the color shade of mark region.

1. Size the line
you can use the field quantity to size the line by drag and drop the QUANTITY field to the Size region in the mark field.

The finished figue like below.
![PointConnect](C:\tableau\PointConnect.png)
