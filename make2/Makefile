
all: main

main:src1.o src2.o src3.o main.o
	gcc $^ -o $@

main.o:main.c
	gcc -c $<

.PHONY: clean
clean:
	rm -f main *.o

include src1.mk
include src2.mk
include src3.mk
