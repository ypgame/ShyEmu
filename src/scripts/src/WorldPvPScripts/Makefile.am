INCLUDES = -I$(top_srcdir)/src/shyemu-logonserver \
   -I$(top_srcdir)/src/shyemu-realmserver -I$(top_srcdir)/src/shyemu-shared -I$(top_srcdir)/src/shyemu-voicechat \
   -I$(top_srcdir)/src/shyemu-world -I$(srcdir) -I$(srcdir)/../../../../dep/include \
   -I$(srcdir)/../../../../dep/src -I$(srcdir)/../../../../src
INCLUDES += -I$(srcdir)/../../../shyemu-shared/g3dlite -I$(srcdir)/../../../shyemu-shared/vmap
AM_CXXFLAGS = -DSCRIPTLIB

lib_LTLIBRARIES = libWorldPvPScripts.la

libWorldPvPScripts_la_SOURCES = Setup.cpp \
ZoneHellfirePeninsula.cpp \
ZoneSilithus.cpp \
ZoneTerokkarForest.cpp \
ZoneZangarmarsh.cpp
