# hfold

A smarter `fold(1)`, written in Haskell.

## Usage

```
Usage: hfold [-w|--width WIDTH] [PATH]
  Intelligently wrap lines to a given length

Available options:
  -h,--help                Show this help text
  -w,--width WIDTH         Specify a line width to use instead of the default 80
                           columns
  PATH                     Path to input file. If not provided, hfold will
                           attempt to read from STDIN
```
