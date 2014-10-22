SASS Style Guide
=====================================

Order SASS Statement by:
1. extend
2. regular css
3. include
4. child

Always use mixin for vendor

Maximum 3 level deep nesting

Table of contents
```
/* Vendor Dependencies */
@import "compass";

/* Authored Dependencies */
@import "global/colors";
@import "global/mixins";

/* Patterns */
@import "global/tabs";
@import "global/modals";

/* Sections */
@import "global/header";
@import "global/footer";
```


Break Into As Many Small Files As Makes Sense

Variablize All Common Numbers, and Numbers with Meaning

Variablize All Colors

Nest and Name Your Media Queries
```
@include bp(tablet) {
   width: 25%;
}
```

import quick fix sass files last