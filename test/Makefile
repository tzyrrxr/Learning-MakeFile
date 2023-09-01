#test := $(%.c,%.o,$(wildcard *.c *.h))
#VPATH = vpath_test
#vpath %h vpath_test

all: test1.c test2.c
	@echo "all"

test1.c test2.c &:
	@echo "all_1"
	@echo "all_2"

#one:
#	@echo "one"

#sec:
#	echo "sec"
#
#third:
#	echo "third"
#
#
#all:  test1.o test2.o #test3.o
#	echo test
##.PHONY : all
#
#test1.o: test1.c
#	gcc -Wall -c test1.c
#
#test2.o: test2.c
#	gcc -Wall -c test2.c
#
##test1.o: test1.c
##	gcc -Wall -c test1.c
##
##test2.o: test2.c
##	gcc -Wall -c test2.c
##
##test3.o: vpath_test/test3.c vpath_test/test3.h
##	gcc $^ -o $@




clean:
	rm -rf *.o
	rm -rf a.out
	rm -rf *.*~
	rm -rf *~
