.POSIX:
.SUFFIXES:
.PHONY: all clean install check
all:
PROJECT   =sed-mv
VERSION   =1.0.0
PREFIX    =/usr/local
BUILDDIR ?=/home/harkaitz/.build

all:
clean:
install:
check:
## -- BLOCK:license --
install: install-license
install-license: 
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp COPYING $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/sed-mv           $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
