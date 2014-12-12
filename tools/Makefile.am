AM_CFLAGS = $(libcrippy_CFLAGS) $(libmacho_CFLAGS) -I$(top_srcdir)/include
AM_LDFLAGS = $(libcrippy_LIBS) $(libmacho_LIBS)

bin_PROGRAMS = hfsplus

hfsplus_SOURCES = hfs.c
hfsplus_CFLAGS = $(AM_CFLAGS)
hfsplus_LDFLAGS = $(AM_LDFLAGS)
hfsplus_LDADD = $(top_srcdir)/src/libhfsplus-1.0.la