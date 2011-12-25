ACLOCAL_AMFLAGS = -I m4

pkgconfigdir = $(libdir)/pkgconfig

lib_LTLIBRARIES = libnop.la
include_HEADERS = lib/nop.h
sbin_PROGRAMS = nopd
pkgconfig_DATA = libnop.pc

libnop_la_SOURCES = lib/x86.s
libnop_la_LDFLAGS = -version-info 0:0:0

nopd_SOURCES = src/nopd.c lib/nop.h
nopd_CPPFLAGS = -Ilib
nopd_LDFLAGS = libnop.la
