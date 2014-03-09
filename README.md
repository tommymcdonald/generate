generate
========

Bash script to generate files with default headers for a few of my most commonly
used scripting languages.

ex:

`gen cpp newProgram`
creates

`
// newProgram.cpp
#include <iostream>
using namespace std;

int main()
{
  cout << "Hello World!";
}`


If you want to use this, move the `gen` file to your `/usr/bin` directory and run
the `gen 'filetype' 'filename' ` command.

Currently added and supported filetypes are:

`cpp` or `c++`


`perl` or `pl`


`bash` or `sh`
