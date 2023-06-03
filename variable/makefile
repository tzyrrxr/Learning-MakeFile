files := test1.c test2.c
all: $(files)
	echo $(files)
test1.c:
	#echo "*******"
	printf ${files}
test2.c:
	echo "......."

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
