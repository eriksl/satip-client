AC_PREREQ([2.69])
AC_INIT([satip_client], [0.0], [erik@openpli.org])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])

AC_PROG_CC
AC_CONFIG_HEADERS([_config.h])
AC_CONFIG_FILES([Makefile])
AC_CHECK_LIB([pthread], [main])
AC_CHECK_LIB([rt], [main])
AC_CHECK_HEADERS([arpa/inet.h fcntl.h netdb.h netinet/in.h stdlib.h string.h sys/ioctl.h sys/socket.h sys/time.h syslog.h unistd.h])

AC_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_SSIZE_T
AC_TYPE_UINT32_T

AC_FUNC_MALLOC
AC_CHECK_FUNCS([clock_gettime memset setenv socket strchr strdup strerror strstr])

AC_OUTPUT

#AC_ARG_WITH(boxtype,
#	[  --with-boxtype=NAME box type [[none,dm7025,dm800...]]],
#	[BOXTYPE="$withval"],[BOXTYPE="dm800"])
#AC_SUBST(BOXTYPE)
#AC_DEFINE_UNQUOTED(BOXTYPE,"$BOXTYPE",[box type])

#AC_ARG_WITH(machinebuild,
#	[  --with-machinebuild=NAME machine build [[none,atemeo5200,atemeo6000...]]],
#	[MACHINEBUILD="$withval"],[MACHINEBUILD="atemeo5200"])
#AC_SUBST(MACHINEBUILD)
#AC_DEFINE_UNQUOTED(MACHINEBUILD,"$MACHINEBUILD",[machine build])

#if test "$BOXTYPE" == "odinm7" -o "$BOXTYPE" == "e3hd"; then
#	AC_DEFINE(HAVE_NO_MSG16, 1,[define then VTUNER use old MSG 1 Mode])
#fi

#if test "$BOXTYPE" == "vuduo" -o "$BOXTYPE" == "vusolo" -o "$BOXTYPE" == "vuduo2" -o "$BOXTYPE" == "vusolo2" -o "$BOXTYPE" == "vuuno" -o "$BOXTYPE" == "vuultimo" -o "$BOXTYPE" == "vusolose" -o "$BOXTYPE" == "vuzero"; then
#	AC_DEFINE(VMSG_TYPE1, 1,[define vtuner_message type 1 see vtuner.h])
#fi
