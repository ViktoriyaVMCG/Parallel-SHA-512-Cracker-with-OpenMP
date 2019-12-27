# Parallel-SHA-512-Cracker-with-OpenMP



Compile the program with the following flags:

gcc -fopenmp -lcrypt -std=c99 -o parshacrk parshacrk.c

To execute our program:

./parshacrk 1 2 3

Example :
./parshacrk /usr/share/wordlists/rockyou.txt '$6$IUUHDOMU$' '$6$IUUHDOMU$hagBbYm9zywgkLFIJQkM4JpskT8xjxbBlhlFjAXVt1t.XfomJUmG/7Hh79uWETekDzbwsbSxLXkXdEc7j7gPz.'
