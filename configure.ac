AC_INIT([TEMPLATE], [0.0.1], [], [])
AM_INIT_AUTOMAKE([foreign no-dist-gzip dist-xz subdir-objects])

#Find AR and RANLIB for lto support before initializing libtool
AC_CHECK_TOOL([AR],gcc-ar)
AC_CHECK_TOOL([RANLIB],gcc-ranlib)
LT_INIT

AC_PROG_CC
AM_PROG_AS
AC_CHECK_TOOL([OBJCOPY],objcopy)

# Checks for typedefs, structures, and compiler characteristics.
AC_C_INLINE
AC_TYPE_UINT32_T

# Checks for library functions.

AC_CONFIG_FILES([Makefile])

AC_OUTPUT

