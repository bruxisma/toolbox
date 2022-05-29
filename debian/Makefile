GNUMAKEFLAGS += --no-builtin-rules --jobs
.SUFFIXES:
.SUFFIXES: .pkgbuild
.PHONY: all

makedebs := $(patsubst %.pkgbuild,%.deb,$(wildcard *.pkgbuild))

%.deb: %.pkgbuild
	makedeb --file $<

all: $(makedebs)
