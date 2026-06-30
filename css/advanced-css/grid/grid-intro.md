# DISPLAY : GRID 

grid is basically a 2d  components which is used to allign the pages according to their creativity you wonder am saying the same thing to flexbox ..but here is the truth flexbox is 1d used for align row or columns but grid is used to allign all layout like the navigation bar is on the left and this thing is on right  

-------
## FLEXBOX vs GRID *

    flexbox  : 1d component (row or column)
    grid     : 2d component(row and column)


    flexbox : for symmetric 
    grid    : for assymetric 

#### Use Flexbox When:

You need a straight line of items.You are building a navigation bar.You are centering a single item.Your items dictate their own size.

#### use grid when: 

You need strict alignment across rows and columns.You are building a full-page website layout.You need cards to align perfectly both vertically and horizontally.You want elements to overlap on purpose.


example : 

````
.container {
   display : grid;
   grid-template-columns: 1fr 1fr;
    // 1 fr -fractional is used to have equal spacing
   grid-template-rows: 1fr 1fr;
   gap: 10px;

}
````