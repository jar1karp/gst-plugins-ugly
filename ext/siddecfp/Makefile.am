plugin_LTLIBRARIES = libgstsidfp.la

libgstsidfp_la_SOURCES = gstsiddecfp.cpp
libgstsidfp_la_CXXFLAGS = $(GST_PLUGINS_BASE_CFLAGS) $(GST_BASE_CFLAGS) \
	$(GST_CXXFLAGS) $(SIDPLAYFP_CFLAGS)
libgstsidfp_la_LIBADD = $(GST_PLUGINS_BASE_LIBS) $(GST_BASE_LIBS) $(GST_LIBS) $(SIDPLAYFP_LIBS) \
		      -lgstaudio-$(GST_API_VERSION)
libgstsidfp_la_LDFLAGS = $(GST_PLUGIN_LDFLAGS)
libgstsidfp_la_LIBTOOLFLAGS = $(GST_PLUGIN_LIBTOOLFLAGS)

noinst_HEADERS = gstsiddecfp.h
