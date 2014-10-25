IE solutions
==========

#ie8
- When you have images that get chop off, use backstretch.js to fix them
- Make sure all scripts are loaded before any script tags are placed on the page

Fixes IE
```
<!--[if IE]>
	<link rel="stylesheet" type="text/css" href="all-ie-only.css" />
<![endif]-->
```

Fixes to everything BUT IE
```
<!--[if !IE]><!-->
	<link rel="stylesheet" type="text/css" href="not-ie.css" />
 <!--<![endif]-->
 ```

 Fixes IE9 and below
 ```
 <!--[if lt IE 9]>
	<link rel="stylesheet" type="text/css" href="ie8-and-down.css" />
<![endif] -->

<!--[if !IE 6]><!-->
  <link rel="stylesheet" type="text/css" media="screen, projection" href="REGULAR-STYLESHEET.css" />
<!--<![endif]-->

<!--[if gte IE 7]>
  <link rel="stylesheet" type="text/css" media="screen, projection" href="REGULAR-STYLESHEET.css" />
<![endif]-->
 ```