dnl Copyright (c) 2013 Red Hat, Inc. <http://www.redhat.com>

dnl This file is part of structured-sources
dnl

dnl Every other copy of the package version number gets its value from here
AC_INIT([structured-sources], 0.1.1, fharshav@redhat.com, ,[https://github.com/unicorn-uno/structured-sources])

AM_INIT_AUTOMAKE

AC_GNU_SOURCE

AC_SUBST(VERSION)
ISODATE=`date +%Y-%m-%d`
AC_SUBST(ISODATE)

AC_CONFIG_FILES([Makefile
		formula/Makefile
		bin/Makefile
		bin/sources
		doc/Makefile])

AC_OUTPUT
