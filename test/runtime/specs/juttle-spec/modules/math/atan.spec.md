The `Math.atan` function
========================

Produces an error when passed an argument of incorrect type
-----------------------------------------------------------

### Juttle

    emit -from Date.new(0) -limit 1 | put result = Math.atan(null) | view result

### Warnings

  * Invalid argument type for "Math.atan": expected number, received null.
