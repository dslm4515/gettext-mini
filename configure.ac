AC_PREREQ([2.69])
AC_INIT([gettext-tiny], [0.3.1], [mlfs.dev@gmail.com])
AC_CONFIG_SRCDIR([src/bin/msgfmt.c])
AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE
AC_PROG_LIBTOOL
AC_CONFIG_MACRO_DIRS([m4])

# Checks for programs.
AC_PROG_CC
AC_LANG([C])

# Checks for header files.
AC_CHECK_HEADERS([limits.h locale.h stddef.h stdint.h stdlib.h string.h])
AC_HEADER_STDC

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_SIZE_T
AC_TYPE_UINT32_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_CHECK_FUNCS([memset strcasecmp strchr strpbrk strrchr strspn strstr])

AC_CONFIG_FILES([Makefile
                 src/bin/Makefile
                 src/lib/Makefile])
AC_OUTPUT
