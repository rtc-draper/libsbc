
aclocaldir = $(datadir)/aclocal

aclocal_DATA = sbc.m4

pkgconfigdir = $(libdir)/pkgconfig

pkgconfig_DATA = sbc.pc

EXTRA_DIST = $(aclocal_DATA)

DISTCLEANFILES = $(pkgconfig_DATA)

MAINTAINERCLEANFILES = Makefile.in \
	aclocal.m4 configure config.h.in config.sub config.guess \
	ltmain.sh missing install-sh mkinstalldirs
