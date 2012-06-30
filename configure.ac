#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([sunmake], [2006.12.19], [pashev.igor@gmail.com])
AC_CONFIG_SRCDIR([usr/src/make_src/Make/bin/make/common/nse_printdep.cc])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([foreign])
AM_SILENT_RULES([silent])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET
LT_INIT


# Checks for libraries.

# Checks for header files.
AC_FUNC_ALLOCA
AC_CHECK_HEADERS([arpa/inet.h fcntl.h limits.h locale.h netdb.h netinet/in.h nl_types.h stdlib.h string.h sys/file.h sys/mount.h sys/param.h sys/socket.h sys/systeminfo.h sys/time.h sys/vfs.h unistd.h wchar.h wctype.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_TYPE_UID_T
AC_C_INLINE
AC_TYPE_MODE_T
AC_TYPE_OFF_T
AC_TYPE_PID_T
AC_TYPE_SIZE_T
AC_TYPE_SSIZE_T
AC_CHECK_DECLS([sys_siglist])
AC_CHECK_TYPES([u_int16_t])

# Checks for library functions.
AC_FUNC_CHOWN
AC_FUNC_FORK
AC_FUNC_LSTAT_FOLLOWS_SLASHED_SYMLINK
AC_FUNC_MALLOC
AC_CHECK_FUNCS([alarm atexit dup2 getcwd gethostbyname memchr memset mkdir putenv rmdir setenv setlocale strcasecmp strchr strdup strerror strrchr strstr uname])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
