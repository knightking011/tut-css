# POSITIONING ! 

#### there are four types of positioning 
    1 . Static   positioning
    2 . Relative positioning
    3 . Absolute positioning
    4 . Fixed    positioning

### 1. static positioning 
Static positioning is the default layout method where elements flow naturally on the page and cannot be moved with offset properties (top, left)
````css
position:static;
top:20px;
side:20px;
````

### 2 .Relative positioning 

Relative positioning also stays in the normal flow, but it allows you to shift the element visually from its original spot
````css
positioning:relative;
side:20px;
top:20px;
````

### 3 . Absolute Positiong 
absolute positioning (position: absolute) removes an element from the normal document flow and positions it relative to its nearest positioned ancestor (an element with position: relative, absolute, or fixed). If no ancestor is positioned, it defaults to the root HTML page.
 
 ##### How It Works ?When you set position: absolute, the element is taken completely out of the layout. Other elements on the page will act as if the absolutely positioned element does not exist.

 ````css
 /* The container */
.parent-container {
  position: relative; /* This creates the positioning boundary */
  width: 300px;
  height: 300px;
}

/* The element you want to place */
.child-badge {
  position: absolute;
  top: 10px;
  right: 10px;
}
````

### 4 .Fixed positioning 

it is described as the picture aligned in the fixed state even when we move or scroll down the page the pic was still there that is called as fixed positioning 

````css
position:fixed;
top:20px;
side:20px;
````


