BUILDPATH=../build/
CC=gcc
CFLAGS=-Wall -Werror -Wextra -std=c11
BUILDFILES=s21_cat.o

build: $(BUILDFILES)
	$(CC) $(CFLAGS) $(BUILDFILES) -o s21_cat

test:
	sh test.sh

all: build test

clean:
	rm -rf ./*.o
	rm -rf cat

rebuild: clean all