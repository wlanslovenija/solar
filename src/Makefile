all: solar

solar: main.o pli.o
	$(CC) $(LDFLAGS) -o $@ $^

%.o: %.c
	$(CC) $(CFLAGS) $(EXTRA_CFLAGS) -c -I. -o $@ $<

clean:
	rm -rf *.o solar
