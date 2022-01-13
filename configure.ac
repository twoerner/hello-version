dnl Copyright (C) 2022  Trevor Woerner <twoerner@gmail.com>

dnl AC_PREREQ(2.57)
AC_INIT([Hello Version], 2.0.0, twoerner@gmail.com, hello-version)
AC_CONFIG_SRCDIR(src/main.c)
AC_CONFIG_AUX_DIR(cfg)
AM_INIT_AUTOMAKE([foreign no-dist-gzip dist-bzip2 1.9])
AM_CONFIG_HEADER(cfg/config.h)

SUBDIRS="src"

dnl **********************************
dnl checks for programs
dnl **********************************
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL

dnl **********************************
dnl checks for header files
dnl **********************************
AC_HEADER_STDC

dnl **********************************
dnl other stuff
dnl **********************************
AC_SUBST(SUBDIRS)

dnl **********************************
dnl output
dnl **********************************
AC_OUTPUT(Makefile
cfg/Makefile
src/Makefile)
