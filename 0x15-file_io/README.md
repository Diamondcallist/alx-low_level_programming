Tread lightly, she is near : A function that reads a text file and prints it to the POSIX standard output.
Prototype: ssize_t read_textfile(const char *filename, size_t letters);
Where letters is the number of letters it should read and print.
Returns the actual number of letters it could read and print.
If the file can not be opened or read, return 0.
If filename is NULL return 0
If write fails or does not write the expected amount of bytes, return 0.
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main/0-main.c 0-read_textfile.c -o a
Run this way: ./a main/Requiescat
