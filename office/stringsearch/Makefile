CC=/usr/ensta/pack/simplescalar-3v0d/bin/sslittle-na-sstrix-gcc

FILE1 = bmhasrch.c  bmhisrch.c  bmhsrch.c  pbmsrch_small.c
FILE2 = bmhasrch.c  bmhisrch.c  bmhsrch.c  pbmsrch_large.c

all: search_small search_large

search_small: ${FILE1} Makefile
	$(CC) -static ${FILE1} -O3 -o search_small.ss

search_large: ${FILE2} Makefile
	$(CC) -static ${FILE2} -O3 -o search_large.ss

clean:
	rm -rf search_small.ss search_large.ss output*
