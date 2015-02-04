# FileEditor
This was a file editor that I worked on with a partner for the final project in our Operating Systems class.  Parts of the code base referencing the class or the professor have been removed, so as to not give future students an unfair advantage.

The file editor works as a linked list of lines: each line is a char array ending in '\n'.  The linked list allows us to remove lines and add them easily.

When a "write" change is sent, it sends a syscall to the operating system that writes the file back to memory in blocks (in this project, our block size was 512 bytes).
