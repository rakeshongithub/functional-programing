# Functions Programing
JavaScript functional programing.

# “Array” Methods

`__.chunk(array, [size])` - Creates an array of elements split into groups the length of size. If array can't be split evenly, the final chunk will be the remaining elements.

`__.compact(array)` - Creates an array with all falsey values removed. The values false, null, 0, "", undefined, and NaN are falsey.

`__.compactDeep(array)` - Same as `__.compact` but remove the flasey values recursively.

`__.concat(array, [values])` - Creates a new array concatenating array with any additional arrays and/or values.