AC_INIT([sensible-utils],[SENSIBLE_UTILS_VERSION])

AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_AUX_DIR([build-aux])
AM_INIT_AUTOMAKE
AC_CHECK_PROGS([PO4A], [po4a])
AS_IF([test X$PO4A = X],AC_MSG_ERROR([Need po4a program]))

AC_CONFIG_FILES([Makefile man/Makefile])
AC_OUTPUT
