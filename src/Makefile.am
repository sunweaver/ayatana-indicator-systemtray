systemtraylibdir = $(INDICATORDIR)
systemtraylib_LTLIBRARIES = libsystemtray.la
libsystemtray_la_SOURCES =	\
	fixedtip.c		\
	fixedtip.h		\
	gnome-bg-slideshow.c	\
	gnome-bg-slideshow.h	\
	indicator-systemtray.c	\
	na-marshal.c		\
	na-marshal.h		\
	na-tray.c		\
	na-tray-child.c		\
	na-tray-child.h		\
	na-tray.h		\
	na-tray-manager.c	\
	na-tray-manager.h
libsystemtray_la_CFLAGS = \
	$(INDICATOR_CFLAGS) \
	-Wall \
	-DG_LOG_DOMAIN=\"Ayatana-Indicator-SystemTray\"
libsystemtray_la_LIBADD = \
	$(INDICATOR_LIBS)
libsystemtray_la_LDFLAGS = \
	-module \
	-avoid-version
