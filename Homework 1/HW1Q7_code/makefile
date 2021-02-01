# To run, enter 
# make all

all: testpid

testpid: test_1_2.o pid_1_2.o
	gcc  -pthread -o testpid test_1_2.o pid_1_2.o

pid_1_2.o: pid_1_2.c pid_1.h
	gcc -pthread -c pid_1_2.c

test_1_2.o: test_1_2.c pid_1.h
	gcc -pthread -c test_1_2.c
