# Go Array Index Out of Bounds

This example demonstrates a common error in Go: accessing an array index that is out of bounds.  Go arrays are zero-indexed, meaning the first element is at index 0, and the last element is at index `len(array) - 1`. Attempting to access an index beyond this range will result in a runtime panic.

The `bug.go` file shows the buggy code, while `bugSolution.go` provides a corrected version.