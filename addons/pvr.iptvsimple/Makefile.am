#
# Makefile for the PVR IPTV Simple add-on for XBMC PVR
#
# See the README for copyright information and
# how to reach the author.
#

ADDONBINNAME    = XBMC_IPTV_Simple
ADDONNAME       = pvr.iptvsimple
LIBNAME         = libpvriptvsimple-addon
lib_LTLIBRARIES = libpvriptvsimple-addon.la

include ../Makefile.include.am

INCLUDES+=-Isrc

libpvriptvsimple_addon_la_LIBADD = -lz
libpvriptvsimple_addon_la_SOURCES = src/client.cpp \
                                    src/PVRIptvData.cpp
libpvriptvsimple_addon_la_LDFLAGS = @TARGET_LDFLAGS@


