#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([hello], [1], [joel@joelburton.com])
AC_CONFIG_SRCDIR([hello.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC_C99
AM_INIT_AUTOMAKE

# Checks for libraries.
PKG_CHECK_MODULES([DEPS], [glib-2.0 >= 2.24.1])
AC_CHECK_LIB([glib-2.0],[g_free])

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
echo \
"-----------------------------------------------------------
Thank you for installing ${PACKAGE_NAME} version ${PACKAGE_VERSION}.
Installation directory prefix: '${prefix}'.
Compilation command: '${CC} ${CFLAGS} ${CPPFLAGS}'
Now type 'make && sudo make install' to generate the program
and install it to your system.
------------------------------------------------------------"
