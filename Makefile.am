AM_CPPFLAGS = -DTEXT_DOMAIN=\"SUNW_OST_OSLIB\"
AM_CPPFLAGS += -DNDEBUG

lib_LTLIBRARIES = libmakestate.la libbsd.la

libmakestate_la_LDFLAGS = -version-info 1:0:0
libmakestate_la_SOURCES = \
usr/src/make_src/Make/lib/makestate/src/ld_file.c \
usr/src/make_src/Make/lib/makestate/src/lock.c

libbsd_la_LDFLAGS = -static
libbsd_la_SOURCES = \
usr/src/make_src/Make/lib/bsd/src/bsd.cc
