AC_INIT
AC_CONFIG_SRCDIR([lzfx.c])

AC_GNU_SOURCE
AC_SYS_LARGEFILE
AC_PROG_CC
AC_PROG_RANLIB
AC_PROG_INSTALL
AC_HEADER_STDC

AC_C_CONST
AC_C_INLINE

if test "$GCC" = yes; then
   CFLAGS="$CFLAGS -O3 -funroll-all-loops"
else
   AC_MSG_RESULT(no gcc)
fi

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
