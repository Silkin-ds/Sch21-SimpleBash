CFLAGS=-Wall -Werror -Wextra -std=c11
FILE= 1.txt
s21_grep: grep.o
	gcc $(CFLAGS) grep.o -o s21_grep

grep.o:
	gcc $(CFLAGS) -c grep.c

test:
	sh test_func_grep.sh

all: s21_grep test

clean:
	rm -rf ./*.o
	rm -rf s21_grep

rebuild: clean all
