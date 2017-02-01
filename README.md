# lily-repl

### Version 1.0.0

This package provides a simple repl for Lily. The repl is able to print out
single expressions, or parse statements. The repl will change prompts if the
last command sent was not complete. As this is a simple repl, there is no
support for history or navigation with the arrow keys.

The repl file is small because it uses `spawni` to create an interpreter inside
of an interpreter. The sub interpreter does the actual lifting.

### Requirements

Only `FascinatedBox/spawni` is required.
