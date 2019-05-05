# CPE_get_next_line_2018

Recoded a simplified version of the lib c function "getline"

It return the next line from file descriptor (fd) at each call as a char * with a \0 at the end.
Return NULL when no more line is available

Only using the following functions : read, malloc, free
