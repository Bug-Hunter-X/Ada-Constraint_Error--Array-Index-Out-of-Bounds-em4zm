# Ada Constraint_Error: Array Index Out of Bounds

This repository demonstrates a common error in Ada programming: accessing an array element using an index that is outside the defined range of the array.  Ada arrays are 1-based, meaning the first element is at index 1, not 0 as in some other languages (like C, Java, etc.).

The `bug.ada` file contains code that will cause a `Constraint_Error` exception when run. The `bugSolution.ada` file shows the corrected code.

**How to reproduce the error:**

1. Compile `bug.ada` using an Ada compiler (like GNAT).
2. Run the compiled executable.
3. Observe the `Constraint_Error` exception.

**Solution:**

Refer to `bugSolution.ada` for the correct implementation.  The primary fix is to ensure that all array accesses use valid indices within the range defined for the array.