# task61
contact_list.h - файл, в котором определены структуры и функции.
contact_list.c - файл, в котором реализованы функции для работы с двусвязным списком.
необходимо скомпилировать contact_list.c в статическую библиотеку.
gcc -c contact_list.c -o contact_list.o
ar rcs libcontact_list.a contact_list.o
task61.c - файл, который использует библиотеку.
gcc task61.c -o task61 -L. -lcontact_list
./task61
