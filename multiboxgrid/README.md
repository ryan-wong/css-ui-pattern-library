Multi Box Grid
=====================
Have you ever need to have boxes that scale as the page shrinks and need all elements postion to stay the same? This mixin helps you do it.

This technique is very useful when you need to keep image responsive to the page and have overlaying text positioned at specific places.

How it works:
- first you have a class box that you make position relative
- then you set the pseudo CSS to have before box property push padding downward by the ratio you want
- then inside the box, you add a position absolute div content that fills the box
- now any element you put inside content are in position absolute. try making all positions percentages and it will scale

This technique is very useful for the scaling 3 grid boxes to mobile easily without breaking much code