CC             = gcc
CFLAGS         = -Wall -g -O2 -std=c99

all: simple

simple: ../ringbuffer.c simple.c
	$(CC) $(CFLAGS) -o simple simple.c ../ringbuffer.c

tail: ../ringbuffer.c tail.c
	$(CC) $(CFLAGS) -o tail tail.c ../ringbuffer.c

clean:
	rm -f simple
