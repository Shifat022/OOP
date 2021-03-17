all = myapp

myapp: main.o getch.o getop.o stack.o
	gcc -Wall -o myapp main.o getch.o getop.o stack.o


main.o: main.c
	gcc -c main.c

getch.o: getch.c
	gcc -c getch.c

getop.o: getop.c
	gcc -c getop.c
stack.o: stack.c
	gcc -c stack.c
