# F# Mutability Bug

This repository demonstrates a common error related to mutability in F#.  The issue involves using mutable variables with functions, where changes to the mutable variables outside the function do not automatically update the function's behavior.  The `bug.fs` file contains the buggy code, while `bugSolution.fs` shows how to correctly handle mutability in this scenario.