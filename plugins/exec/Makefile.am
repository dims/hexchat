libdir = $(hexchatlibdir)

if OS_W32
lib_LTLIBRARIES = exec.la
endif
exec_la_SOURCES = exec.c
exec_la_LDFLAGS = -avoid-version -module -no-undefined
exec_la_LIBADD = 
AM_CPPFLAGS = $(COMMON_CFLAGS) -I$(srcdir)/../../src/common

