#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([TICPP-TWO], [2.0], [BUG-REPORT-ADDRESS])
AC_CONFIG_SRCDIR([TESTHEADER_require.cpp])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_MAKE_SET

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_SIZE_T
AC_CHECK_TYPES([ptrdiff_t])

# Checks for library functions.
AC_FUNC_ERROR_AT_LINE
AC_FUNC_MALLOC
AC_CHECK_FUNCS([mkdir pow sqrt])

AC_CONFIG_FILES([C01/makefile
                 C02/makefile
                 C03/makefile
                 C04/makefile
                 C05/makefile
                 C06/makefile
                 C07/makefile
                 C08/makefile
                 C09/makefile
                 C0B/makefile
                 C10/makefile
                 C11/makefile
                 TestSuite/makefile
                 makefile])
AC_OUTPUT
