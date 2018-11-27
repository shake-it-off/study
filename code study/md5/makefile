CC=g++
CFLAGS=-Wall -g -O2
LIBS=-lcrypto
 
all: md5
 
md5: md5.cpp
	$(CC) $(CFLAGS) md5.cpp -o $@ $(LIBS)
 
clean:
	@rm -rf md5 md5.dSYM
