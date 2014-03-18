libdir = $(hexchatlibdir)

if OS_W32
lib_LTLIBRARIES = upd.la
endif
upd_la_SOURCES = upd.c
upd_la_LDFLAGS = -avoid-version -module -no-undefined
upd_la_LIBADD = -lwininet
AM_CPPFLAGS = $(COMMON_CFLAGS) -I$(srcdir)/../../src/common

