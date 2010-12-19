#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_INIT([vo-aacenc], [0.1.0], [])
AC_CONFIG_AUX_DIR(.)
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([tar-ustar])
AC_CONFIG_HEADERS([config.h])
AM_MAINTAINER_MODE

# Cross compiling support
AC_CANONICAL_BUILD
AC_CANONICAL_HOST

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET

# Setup for libtool
AC_PROG_LIBTOOL
AC_SUBST(LIBTOOL_DEPS)

# Checks for libraries.
AC_CHECK_LIB([], [main])

# Checks for header files.
AC_CHECK_HEADERS([stdint.h stdlib.h string.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_C_INLINE
AC_TYPE_INT16_T
AC_TYPE_INT32_T
AC_TYPE_INT64_T
AC_TYPE_INT8_T
AC_TYPE_UINT16_T
AC_TYPE_UINT32_T
AC_TYPE_UINT64_T
AC_TYPE_UINT8_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_CHECK_FUNCS([memset])

# soname version to use
# goes by ‘current[:revision[:age]]’ with the soname ending up as
# current.age.revision.
VO_AACENC_VERSION=0:1:0
AC_SUBST(VO_AACENC_VERSION)

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
