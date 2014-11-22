Overflowing text
===================
This makes paragraph show .. at end of too large boxes
```
@mixin text-overflow(){
	overflow:hidden;
	text-overflow:ellipsis;
	white-space: nowrap;
}

.textbox{
	display:block;
	width: 500px;
	@include text-overflow;
}
```