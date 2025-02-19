# F# Mutable Variable Swap Bug

This example demonstrates a common misconception when working with mutable variables in F#.  The `swap` function attempts to exchange the values of `x` and `y`, but due to how mutability works in F#, it fails to modify the original variables passed as arguments. 

The solution shows the correct approach for swapping using a tuple.