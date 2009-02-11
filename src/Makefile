# Mitar <mitar@tnode.com>
# http://mitar.tnode.com/
# In kind public domain.
#
# $Id$
# $Revision$
# $HeadURL$

all: solar

solar: main.o pli.o
	$(CC) -o $@ $^

%.o: %.c
	$(CC) $(CFLAGS) $(EXTRA_CFLAGS) -c -I. -o $@ $<

clean:
	rm -rf *.o solar
