CFLAGS = -ansi -pedantic-errors -Wall -Wextra
LDLIBS = -lm

HEADERS = bookshouse.h 

bookshouse: bookshouse.o 
	gcc bookshouse.o $(LDLIBS) -o bookshouse


bookshouse.o : bookshouse.c $(HEADERS)
	gcc $(CFLAGS) -c bookshouse.c -o bookshouse.o



# Attention, il faut une tabulation avant chaque commande.
