# Unexpected Multiple Return Values in Tcl

This repository demonstrates a common, yet subtle, error in Tcl: returning multiple values from a procedure when only one is expected.  This can lead to difficult-to-debug issues.

The `bug.tcl` file contains the erroneous code. The `bugSolution.tcl` file shows the corrected version.

## How to Reproduce

1.  Clone this repository.
2.  Run `tclsh bug.tcl` (the result will be unexpected).
3.  Run `tclsh bugSolution.tcl` (the result will be as expected).