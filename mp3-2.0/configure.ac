#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.
# autoconf最低版本
AC_PREREQ([2.69])
# 初始化包信息
AC_INIT(mp3, 2.0, 123@qq.com)
# 检测必定存在的文件判断是否运行在正确的目录
AC_CONFIG_SRCDIR([src/app/player.c])
# 生成的宏文件
AC_CONFIG_HEADERS([config.h])
# 关联automake
AM_INIT_AUTOMAKE
# Checks for programs.
AC_PROG_CC

# Checks for libraries.
# 需要生成静态库和动态库
AC_PROG_RANLIB
AC_PROG_LIBTOOL
# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_OUTPUT(Makefile
        src/Makefile
        src/app/Makefile
        src/usb/Makefile
        src/lcd/Makefile
        src/media/Makefile
        src/math/Makefile
        src/inc/Makefile)
