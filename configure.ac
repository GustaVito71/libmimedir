dnl Process this file with autoconf to produce a configure script.
AC_INIT([libmimedir], [0.5.2])
AM_INIT_AUTOMAKE([foreign])
AC_CONFIG_SRCDIR([dirlex.l])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIRS([m4])
AC_CONFIG_FILES([Makefile])

AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET
AC_PROG_YACC
AC_PROG_LEX([noyywrap])
LT_INIT

dnl Checks for programs.

dnl Checks for header files.
AC_CHECK_HEADERS(unistd.h sys/types.h string.h)

dnl Checks for typedefs, structures, and compiler characteristics.
AC_C_CONST
AC_TYPE_SIZE_T

dnl Checks for library functions.
AC_OUTPUT
