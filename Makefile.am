EXTRA_DIST = AUTHORS COPYING INSTALL LICENSE NEWS README README.md

SUBDIRS = bin doc formula

gitclean: distclean
	find . -name Makefile.in -exec rm -f {} \;
	find . -name Makefile -exec rm -f {} \;
	rm -fr autom4te.cache
	rm -f missing aclocal.m4 config.h.in config.guess config.sub ltmain.sh install-sh configure depcomp
