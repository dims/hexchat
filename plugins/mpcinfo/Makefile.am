libdir = $(hexchatlibdir)

if OS_W32
lib_LTLIBRARIES = mpcinfo.la
endif
mpcinfo_la_SOURCES = mpcInfo.c
mpcinfo_la_LDFLAGS = -avoid-version -module -no-undefined
mpcinfo_la_LIBADD = 
AM_CPPFLAGS = $(COMMON_CFLAGS) -I$(srcdir)/../../src/common

