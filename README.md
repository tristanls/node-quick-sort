# quick-sort

_Stability: 1 - [Experimental](https://github.com/tristanls/stability-index#stability-1---experimental)_

Quick sort.

## Usage

```javascript
var quickSort = require('quick-sort');
...
var ascending  = quickSort(array);                              // sort ascending
var descending = quickSort(array, undefined, undefined, false); // sort descending
```

_yes, the descending case is sort of crappy usage, I doubt anyone will use this code though :)_