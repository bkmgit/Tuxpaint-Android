bin_PROGRAMS = csslint-0.6
#man_MANS = csslint.1

csslint_0_6_SOURCES = csslint.c

croco_lib=$(top_builddir)/src/@CROCO_LIB@
LDADD=$(croco_lib)

INCLUDES=-I$(top_srcdir)/intl \
	-I$(top_srcdir)/src \
	-I$(top_builddir)/src \
	$(CROCO_CFLAGS)

csslint_0_6_LDFLAGS=$(CROCO_LIBS)
AM_CFLAGS=$(INCLUDES)

#EXTRA_DIST = $(man_MANS)
