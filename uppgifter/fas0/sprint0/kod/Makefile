fib-rec: fib-rec.c
	gcc -Wall -ggdb -o fib-rec fib-rec.c

fib-iter: fib-iter.c
	gcc -Wall -ggdb -std=c99 -o fib-iter fib-iter.c

fib-count: fib-count.c
	gcc -Wall -ggdb -std=c99 -o fib-count fib-count.c

fib-memo: fib-memo.c
	gcc -Wall -ggdb -std=c99 -o fib-memo fib-memo.c

fib: fib-rec fib-iter fib-count fib-memo

unit: unit-test-example.c minute.c minute.h
	gcc -Wall -ggdb -o unit-test-example unit-test-example.c minute.c
