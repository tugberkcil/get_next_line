# get_next_line
A project at 42 is called Get Next Line.

A line ending with a newline character can be read from a file descriptor using this function, which reads files. The function grabs the following line when you run it again on the same file. In order to prevent leaks, this project addresses memory allocation and when to free and allocate memory.

If there was a mistake, a (-1) is given back. If the file reading is complete, a (0) is given back. And if a line is read, a (1) is returned.
