# quinnc

* It has no options
* It doesn't compile things that work better with native support

```
Usage:
  quinnc <source dir> <target dir>    # Compile directories recursively
  quinnc <source file> <target file>  # Compile one file to another
  quinnc <source file>                # Compile one to stdout
  quinnc -                            # Compile from stdin
  quinnc                              # Default: compile from stdin
```

Included:

* Arrow functions
* Classes
* Template strings
* Rest parameters
* Module (import/export), compiling to simple CommonJS
