AC_PREREQ([2.69])
AC_INIT([libnv], [0.0.0], [http://github.com/kaniini/libnv-portable])
AC_CONFIG_SRCDIR([common_impl.h])
AC_CONFIG_HEADERS([config.h])

AC_PROG_CC
AC_USE_SYSTEM_EXTENSIONS
AC_C_BIGENDIAN

AM_INIT_AUTOMAKE([foreign dist-xz subdir-objects])
AM_SILENT_RULES([yes])
LT_INIT

AC_CHECK_HEADERS([fcntl.h stdint.h stdlib.h string.h sys/param.h sys/socket.h unistd.h endian.h sys/endian.h])

AC_CHECK_HEADER_STDBOOL
AC_TYPE_INT64_T
AC_TYPE_SIZE_T
AC_TYPE_SSIZE_T
AC_TYPE_UINT16_T
AC_TYPE_UINT64_T
AC_TYPE_UINT8_T

AC_FUNC_STRNLEN
AC_CHECK_FUNCS([bzero select strcasecmp])
AC_CONFIG_FILES([Makefile libnv.pc])
AC_OUTPUT
