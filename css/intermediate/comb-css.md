# group rule

### the grouping is genrally combining the two or more  selectors to have the same attributes 
````css
selector,selector{
    colour:green
    background_colour:red
}
````
# parent - child css

### we use > symbol for this and the one in the left is child and in the right is parent and it contains high priority
````css
selector1>selector2{
    colour :firebrick
}

.box>p{
    colour:blue
}
````

# ancestor ,descendant css

### we use space for this and the one in the right is ancestor and the one in the left is decendant we use this to carry the same attribute of one css to another css to follow the same attribute remember the keyword we need to use is space 
````css
.box li{
    colour:red
}
````

# chaining css

### its opposite to ancestor,descendant and we use no space for that and its basically we need to write all class,id,or any other attribute to choose and change the particular line by combining its unique class,id etc.,is called as chaining

````css
li.box{
    colour:red
    padding:20px
}
````
##### remember : we need to write in order otherwise it cant able top find the class or line we need to change
