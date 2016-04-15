# Xpress.jl

This is a package under construction. All the implementation was developed and tested in Windows, thus it might run into linux issues.

Reference at:
[FICO optimizer manual](http://www.fico.com/en/node/8140?file=5097)

## Install:

`Pkg.clone("git://github.com/joaquimg/Xpress.jl.git")`

## High priority:

* Create wrapper for: Callbacks.
* XPRSinit issue, environment is harder to keep track of. And to finalize. (use `__init__()` and `atexit()`)
* Create deps.jl to automatically load the instalation PATH.
* Perform license check.
* Test on UNIX .

## TODO list:

* Verify differences from gurobi/cplex wrappers.
* Prepare specific tests for  the library.
* deal with presolve state
* polish quadratic models

