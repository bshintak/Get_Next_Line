# Get_next_line (Gnl)

📖 Get_next_line is a 42 school project.

The instructions were given in the [subject](https://github.com/bshintak/Gnl/blob/master/subject_gnl.pdf).

It is a function that reads a file and allows you to read a line ending with a newline character from a file descriptor. When you call the function again on 
the same file, it grabs the next line. This project deals with memory allocation and when to free and allocate memory to prevent leaks.

- `put_storage` : puts what is in the buffer inside the storage (in the size of the BUFFER_SIZE).
- `verif_buffer` : used to concatenate what already have inside the storage with what will be added from the buffer.
- `verif_storage` : checks to see if there is already a '\n' inside the storage and mark that position.
- `get_next_line` : main of this project, the return will be a line with a '\n' at the end.
