# Convenience stub makefile to call the real Makefile.



OBJEXT = o

# Explicit so that it's the default rule.
all:
	cd .. && $(MAKE) libcroco/all

clean %.a %.$(OBJEXT):
	cd .. && $(MAKE) libcroco/$@

.PHONY: all clean

.SUFFIXES:
.SUFFIXES: .a .$(OBJEXT)
