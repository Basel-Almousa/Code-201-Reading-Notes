## Transforms in CSS
+ With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. 
+ All of these new techniques are made possible by the transform property.
## Transform Syntax 
The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
### 2D Transforms 
+ Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane.
+ Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. 
+ Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth.
#### 2D Rotate 
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.
#### 2D Scale
Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.
## Combining Transforms