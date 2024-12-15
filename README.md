# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The error occurs when the code attempts to access an array element using an index that is outside the valid range of indices for that array.

The `bug.java` file contains code that causes this exception.  The `bugSolution.java` file provides the corrected version.

## How to Reproduce

1. Clone this repository.
2. Compile `bug.java` using a Java compiler (javac).
3. Run the compiled code (java bug).
4. Observe the `ArrayIndexOutOfBoundsException`.

## Solution

The solution involves carefully checking the loop condition to ensure it doesn't exceed the array bounds.