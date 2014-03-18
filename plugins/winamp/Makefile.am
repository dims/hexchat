libdir = $(hexchatlibdir)

if OS_W32
lib_LTLIBRARIES = winamp.la
endif
winamp_la_SOURCES = winamp.c
winamp_la_LDFLAGS = -avoid-version -module -no-undefined
winamp_la_LIBADD = 
AM_CPPFLAGS = $(COMMON_CFLAGS) -I$(srcdir)/../../src/common

