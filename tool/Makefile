%.o: %.c
	$(CC) -c $(CFLAGS) $< -o $@

.PHONY: all clean

all: hello.o
	$(CC)  hello.o -o hello

clean:
	rm *.o
	rm hello

