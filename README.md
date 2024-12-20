# Swift Function Argument Label Error

This repository demonstrates a common error in Swift: forgetting to include argument labels when calling a function.

## The Bug
The `calculateArea` function requires both `length` and `width` arguments, each with its label.  However, the second call to `calculateArea` omits the label `width:`, resulting in a compile-time error.  This highlights the importance of understanding and using argument labels consistently in Swift.

## The Solution
The solution involves calling the `calculateArea` function correctly, including the specified argument labels.