libdir                 = @libdir@
datarootdir            = @datarootdir@
datadir                = @datadir@
includedir             = @includedir@
pkgconfigdir           = $(libdir)/pkgconfig
nodist_pkgconfig_DATA  = libnv.pc

lib_LTLIBRARIES = libnv.la

libnv_la_SOURCES =		\
	msgio.c			\
	nvlist.c		\
	nvpair.c
libnv_la_LDFLAGS = -no-undefined -version-info 0:0:0

noinst_HEADERS =		\
	nvendian.h		\
	nvlist_impl.h		\
	nvpair_impl.h		\
	common_impl.h

dist_doc_DATA = README.md

pkginclude_HEADERS = nv.h
