Triangles CSS
===================
Common practice triangles are like the following:

```CSS
  border-bottom: 10px solid white;
  border-left: 10px solid transparent;
  border-right: 10px solid transparent;  
```  

However in MACOS Firefox, it doesn't like the word transparent. So use following:

```CSS
  border-bottom: 10px solid white;
  border-left: 10px solid rgba(255, 255, 255, 0);
  border-right: 10px solid rgba(255, 255, 255, 0);
  -moz-transform: scale(.9999);
```