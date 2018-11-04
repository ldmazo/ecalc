
AC_PREREQ([2.69])
AC_INIT([ecalcu], [0.1], [ldmazo@gmail.com])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AC_CONFIG_SRCDIR([src/mfcalc.y])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC
AC_PROG_YACC

# Checks for libraries.
AC_CHECK_LIB([m],[cos])

# Checks for header files.
AC_FUNC_ALLOCA
AC_CHECK_HEADERS([libintl.h malloc.h stddef.h stdlib.h string.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_REALLOC
AC_CHECK_FUNCS([floor pow sqrt])
AC_CONFIG_FILES([Makefile
                src/Makefile
                doc/Makefile
])

AC_OUTPUT
