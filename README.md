# LABS
> Simple LaTeX build script using a containerised compiler.

## Installation 
Clone into a location in `$PATH`. Requires [fish](https://fishshell.com).

## Usage
```
Usage: latex COMMAND

Commands:
	new [DIR]   Initialise a new project from template
	            Expects an empty directory or creates one at DIR if present, or CWD
	build       Build project in CWD using latexmk
	clean1      Run the latexmk clean command, keep output files
	clean2      Run the latexmk clean command, delete output files
	clean3      Delete the build directory completely
	help        Print this help text
```
