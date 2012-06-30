AM_CPPFLAGS = -DTEXT_DOMAIN=\"SUNW_OST_OSLIB\"
AM_CPPFLAGS += -DNDEBUG
AM_CPPFLAGS += -Iusr/src/make_src/include

lib_LTLIBRARIES = \
libmakestate.la \
libbsd.la \
libmksdmsi18n.la

libmakestate_la_LDFLAGS = -version-info 1:0:0
libmakestate_la_SOURCES = \
usr/src/make_src/Make/lib/makestate/src/ld_file.c \
usr/src/make_src/Make/lib/makestate/src/lock.c

libbsd_la_LDFLAGS = -static
libbsd_la_SOURCES = \
usr/src/make_src/Make/lib/bsd/src/bsd.cc

libmksdmsi18n_la_LDFLAGS = -static
libmksdmsi18n_la_CPPFLAGS = $(AM_CPPFLAGS) -DI18N_VERSION=1
libmksdmsi18n_la_SOURCES = \
usr/src/make_src/Make/lib/mksdmsi18n/src/libmksdmsi18n_init.cc

