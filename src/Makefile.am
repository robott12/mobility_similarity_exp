

# include_HEADERS = geoExp.h geodb.h

LIBINCLUDE = ./../mylibraries/headers/
LIBB 	   = ./../mylibraries/lib/

bin_PROGRAMS = similarity

similarity_SOURCES = similarity.cpp 
#geoExp.cpp geodb.cpp


similarity_LDADD = $(BOOST_SYSTEM_LIBS) $(BOOST_FILESYSTEM_LIBS) $(LIBXMLXX_LIBS) -L$(LIBB) ./../mylibraries/lib/libdfa-1.0.a ./../mylibraries/lib/libedsm-1.0.a ./../mylibraries/lib/liblstar-1.0.a ./../mylibraries/lib/libutilities-1.0.a ./../mylibraries/lib/libsqlite3.a -ldl

similarity_CPPFLAGS = $(BOOST_CPPFLAGS) $(LIBXMLXX_CFLAGS) -std=gnu++11 -I$(LIBINCLUDE) -O2 -fopenmp -ggdb3 

similarity_LDFLAGS = $(BOOST_SYSTEM_LDFLAGS) $(BOOST_FILESYSTEM_LDFLAGS)



# Dynamic library 
#gigeo_LDADD = $(BOOST_SYSTEM_LIBS) $(BOOST_FILESYSTEM_LIBS) $(LIBXMLXX_LIBS) ./../mylibraries/lib/libdfa-1.0.la ./../mylibraries/lib/libedsm-1.0.la ./../mylibraries/lib/liblstar-1.0.la ./../mylibraries/lib/libutilities-1.0.la
