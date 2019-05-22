OPTIONS_AUTOMAKE=gnu
ACLOCAL_AMFLAGS=-I ./m4

lib_LIBRARIES = libthr_pool.a

libthr_pool_a_SOURCES = thr_pool.c
libthr_pool_a_CFLAGS = -I. ${CFLAGS}
libthr_pool_a_includedir=${includedir}
libthr_pool_a_include_HEADERS = thr_pool.h

lib_LTLIBRARIES = libthr_pool.la
libthr_pool_la_SOURCES = thr_pool.c
libthr_pool_la_CFLAGS = -I. ${CFLAGS}
libthr_pool_la_includedir=${includedir}
libthr_pool_la_include_HEADERS = thr_pool.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = thr_pool.pc
pkginclude_HEADERS = thr_pool.h
pkginclude_LIBS = libthr_pool
