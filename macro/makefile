#run = /home/sjlin/MakeFile/macro/test.exe
#name = test
#arr = test.c test2.c test3c
#runThere: test.c
#	echo yes

#${arr}: $$@
#	cc -o $@ $?

#all:
#	@#run = ./test.exe
#	@#${run}
#	@#echo ${name}
#	@#echo $(name)
#run: test.o
#	echo yes
#
#test.o: test.c
#	gcc -c test.c
#test1:
#	echo test1
#test2:
#	echo test2
#test3:
#	echo test3
all: test.c
	gcc test.c -o all
test2:
	echo test2

clean:
	rm -f all
