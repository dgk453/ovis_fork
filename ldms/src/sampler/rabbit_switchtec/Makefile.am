pkglib_LTLIBRARIES =
lib_LTLIBRARIES =
dist_man7_MANS =
dist_man1_MANS =

AM_CPPFLAGS = @OVIS_INCLUDE_ABS@
AM_LDFLAGS = @OVIS_LIB_ABS@
COMMON_LIBADD = -lsampler_base -lldms -lovis_util -lcoll \
		@LDFLAGS_GETTIME@

if ENABLE_rabbit_switchtec
librabbit_switchtec_la_SOURCES = rabbit_switchtec.c 
librabbit_switchtec_la_LIBADD = $(COMMON_LIBADD)
pkglib_LTLIBRARIES += librabbit_switchtec.la
dist_man7_MANS += Plugin_rabbit_switchtec.man
endif


