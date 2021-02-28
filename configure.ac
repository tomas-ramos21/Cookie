AC_INIT([Cookie], [0.0.1], [tomas.ramos.github@gmail.com])

dnl - Verify available version of Autoconf
AC_PREREQ(2.69)

dnl - Verify if either Clang or GCC exist
AC_CHECK_PROGS(CC, [clang gcc], [""])
AC_PROG_CC
AC_SUBST(CC)

dnl - Verify if the standard libraries exist
AC_HEADER_STDC
AC_HEADER_DIRENT
AC_HEADER_STAT
AC_HEADER_STDBOOL
AC_HEADER_SYS_WAIT
AC_CHECK_HEADERS([stddef.h stdint.h])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
