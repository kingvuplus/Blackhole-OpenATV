installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = TuxboxPlugins CutListEditor DVDBurn PicturePlayer DVDPlayer MediaScanner MediaPlayer GraphMultiEPG SocketMMI

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

install_PYTHON =	\
	__init__.py
