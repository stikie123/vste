PREFIX ?= /usr
DESTDIR ?=

vste: vste.c
	gcc -Wall -Wextra -pedantic -std=c99 -o vste vste.c

install: vste
	install -D vste "$(DESTDIR)$(PREFIX)/bin/vste"

clean:
	rm -f vste
