installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = LDteam OpenIPTV TuxboxPlugins CutListEditor PicturePlayer MediaScanner MediaPlayer SocketMMI DVDBurn Modem Volume_adjust ProgrammlistenUpdater RemoteStreamConvert

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

if VUSOLO4K
SUBDIRS += MiniTV QuadPip
endif

if VUULTIMO4K
SUBDIRS += MiniTV QuadPip
endif

if VUUNO4K
SUBDIRS += QuadPip
endif

if HAVE_KODI
SUBDIRS +=  StartKodi
endif

install_PYTHON = __init__.py
