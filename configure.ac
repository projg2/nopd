AC_PREREQ([2.60])
AC_INIT([nopd], [0])
AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([1.6 foreign dist-bzip2 -Wall])

m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES])

AC_PROG_CC
AM_PROG_AS
AM_PROG_CC_C_O
AC_USE_SYSTEM_EXTENSIONS
LT_INIT([disable-static])

AC_CONFIG_HEADER([config.h])
AC_CONFIG_FILES([Makefile libnop.pc])
AC_OUTPUT
