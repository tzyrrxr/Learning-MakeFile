files := test1.o test2.o
all: $(files)
	echo $(files)
test1.o: test1.c
	gcc -g -O -c test1.c
	./test1
test2.o: test2.c
	gcc -g -O -c test2.c
	./test2

create:
	touch $(files)
clean:
	rm -f $(files)
	rm -f makefile~
	rm -f *.*~

# RESULT:
#   test1.c
#   test2.c
#   yes
