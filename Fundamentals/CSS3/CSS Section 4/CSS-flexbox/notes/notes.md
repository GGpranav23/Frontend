NOTE: The flex items width is same as the size of its content.

NOTE: However, the height of flex container is defined by the tallest element among all the flex items. Every flex item has height of the tallest element.

Syntax: align-items: center; 
center: Aligns all the flex items in center with equal margin on top and bottom of flex item
flex-start: aligns the item at the flex start.
flex-end: aligns the item at the flex end.
stretch: It stretches all the elements as tall as every element

Syntax: justify-content: center;
center: Aligns all the flex items in the exact center of the container with equal margins on left and right side

Syntax: flex property is used to define the size of the flex items.
Its a shorthand property for flex-grow, flex-shrink and flex-basis.

Important 
<!-- Defaults -->
flex-grow: 0; 
flex-shrink: 1;
flex-basis: auto;

<!-- Shorthand for above three (USE THIS AT ALL TIMES) -->
flex: flex-grow-value flex-shrink-value flex-basis-value;


NOTE: By default, flexbox shrinks the elements to fit the container (because,by default, flex-shrink is set to 1)

NOTE: flex-grow, when applied to all the flex-items, the items occupy the container's space equally horizontally.

NOTE: if for a flex-item, flex-grow is set to 2, then it gets double the available space of the container. For example, if the container has available space as 600px and there are 5 items then the element with flex-grow set to 2 will get 200px and remaining four items will get 100px each