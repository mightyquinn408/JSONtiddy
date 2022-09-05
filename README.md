# JSONtiddy
A Mac command line app to tiddy up JSON 

OVERVIEW: Adjusts JSON files to compress or expand data, and also provide key sorting.

USAGE: jsontidy [--output <output>] [--force-overwrite] [--prettify] [--sort] <file>

ARGUMENTS:
  <file>                  The filename you want to process.

OPTIONS:
  -o, --output <output>   Writes the output to a file rather than to standard output.
  -f, --force-overwrite   Force overwrite files if they exist already.
  -p, --prettify          Neatly formats the output.
  -s, --sort              Sort keys alphabetically.
  -h, --help              Show help information.
