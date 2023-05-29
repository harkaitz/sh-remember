DESTDIR =
PREFIX  =/usr/local


all:
clean:
install:
update:
## -- install-sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/note             $(DESTDIR)$(PREFIX)/bin
	cp bin/run              $(DESTDIR)$(PREFIX)/bin
	cp bin/todo             $(DESTDIR)$(PREFIX)/bin
	cp bin/trash            $(DESTDIR)$(PREFIX)/bin
	cp bin/alog             $(DESTDIR)$(PREFIX)/bin
	cp bin/alert            $(DESTDIR)$(PREFIX)/bin
	cp bin/changes          $(DESTDIR)$(PREFIX)/bin
## -- install-sh --
## -- license --
install: install-license
install-license: LICENSE
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/sh-remember
	cp LICENSE $(DESTDIR)$(PREFIX)/share/doc/sh-remember
## -- license --
