AM_CPPFLAGS = -DTEXT_DOMAIN=\"SUNW_OST_OSLIB\"
AM_CPPFLAGS += -DNDEBUG
AM_CPPFLAGS += -I$(top_srcdir)/usr/src/make_src/include

AM_CPPFLAGS += $(ARCH_CPPFLAGS)

lib_LTLIBRARIES = \
libmakestate.la \
libbsd.la \
libmksdmsi18n.la \
libmksh.la \
libvroot.la

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
usr/src/make_src/Make/lib/mksdmsi18n/src/libmksdmsi18n_init.cc \
usr/src/make_src/include/avo/intl.h

libmksh_la_LDFLAGS = -static
libmksh_la_CPPFLAGS = $(AM_CPPFLAGS) -I$(top_srcdir)/usr/src/make_src/Make/include
libmksh_la_SOURCES = \
usr/src/make_src/Make/include/mksh/defs.h \
usr/src/make_src/Make/include/mksh/dosys.h \
usr/src/make_src/Make/include/mksh/globals.h \
usr/src/make_src/Make/include/mksh/i18n.h \
usr/src/make_src/Make/include/mksh/libmksh_init.h \
usr/src/make_src/Make/include/mksh/macro.h \
usr/src/make_src/Make/include/mksh/misc.h \
usr/src/make_src/Make/include/mksh/mksh.h \
usr/src/make_src/Make/include/mksh/read.h \
usr/src/make_src/Make/lib/mksh/src/dosys.cc \
usr/src/make_src/Make/lib/mksh/src/globals.cc \
usr/src/make_src/Make/lib/mksh/src/i18n.cc \
usr/src/make_src/Make/lib/mksh/src/macro.cc \
usr/src/make_src/Make/lib/mksh/src/misc.cc \
usr/src/make_src/Make/lib/mksh/src/mksh.cc \
usr/src/make_src/Make/lib/mksh/src/read.cc

libvroot_la_LDFLAGS = -static
libvroot_la_CPPFLAGS = $(AM_CPPFLAGS) -I$(top_srcdir)/usr/src/make_src/Make/include
libvroot_la_SOURCES = \
usr/src/make_src/Make/include/vroot/args.h \
usr/src/make_src/Make/include/vroot/report.h \
usr/src/make_src/Make/include/vroot/vroot.h \
usr/src/make_src/Make/lib/vroot/src/access.cc \
usr/src/make_src/Make/lib/vroot/src/args.cc \
usr/src/make_src/Make/lib/vroot/src/chdir.cc \
usr/src/make_src/Make/lib/vroot/src/chmod.cc \
usr/src/make_src/Make/lib/vroot/src/chown.cc \
usr/src/make_src/Make/lib/vroot/src/chroot.cc \
usr/src/make_src/Make/lib/vroot/src/creat.cc \
usr/src/make_src/Make/lib/vroot/src/execve.cc \
usr/src/make_src/Make/lib/vroot/src/lock.cc \
usr/src/make_src/Make/lib/vroot/src/lstat.cc \
usr/src/make_src/Make/lib/vroot/src/mkdir.cc \
usr/src/make_src/Make/lib/vroot/src/mount.cc \
usr/src/make_src/Make/lib/vroot/src/open.cc \
usr/src/make_src/Make/lib/vroot/src/readlink.cc \
usr/src/make_src/Make/lib/vroot/src/report.cc \
usr/src/make_src/Make/lib/vroot/src/rmdir.cc \
usr/src/make_src/Make/lib/vroot/src/setenv.cc \
usr/src/make_src/Make/lib/vroot/src/stat.cc \
usr/src/make_src/Make/lib/vroot/src/statfs.cc \
usr/src/make_src/Make/lib/vroot/src/truncate.cc \
usr/src/make_src/Make/lib/vroot/src/unlink.cc \
usr/src/make_src/Make/lib/vroot/src/unmount.cc \
usr/src/make_src/Make/lib/vroot/src/utimes.cc \
usr/src/make_src/Make/lib/vroot/src/vroot.cc
