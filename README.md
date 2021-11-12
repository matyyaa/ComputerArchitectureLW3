# Laboratory work #3

Command line tool for string manipulation.

## Usage:

### --help (-h)

Shows the manual for the program.

#### Example

- ./program --help

### --version" (-v)

Shows program version.

#### Example

- ./program --version

### --input (-i)

Creates a string from given input.

#### Arguments

- **$1** (string): The input string.

#### Example

- ./program -iabc

### --output (-o)

Redirects the output to the given file.

#### Arguments

- **$1** (string): The file name.

#### Example

- ./program --output=file.txt

### --count (-c)

Counts the number of members in the string.

#### Example

- ./program -iabc -c

### --reverse (-r)

Reverses order of all members in the string.

#### Example

- ./program -iabc -r
