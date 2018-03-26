NULL = 

directorydir = $(datadir)/desktop-directories
directory_in_files =				\
	moksha-audio-video.directory.in		\
	moksha-development.directory.in		\
	moksha-education.directory.in		\
	moksha-game.directory.in			\
	moksha-graphics.directory.in		\
	moksha-hardware.directory.in		\
	moksha-internet-and-network.directory.in	\
	moksha-look-and-feel.directory.in		\
	moksha-menu-applications.directory.in	\
	moksha-menu-system.directory.in		\
	moksha-network.directory.in		\
	moksha-office.directory.in		\
	moksha-other.directory.in			\
	moksha-personal.directory.in		\
	moksha-science-math.directory.in		\
	moksha-settings.directory.in		\
	moksha-settings-system.directory.in	\
	moksha-system.directory.in		\
	moksha-system-tools.directory.in		\
	moksha-utility-accessibility.directory.in	\
	moksha-utility.directory.in		\
	$(NULL)

directory_DATA = $(directory_in_files:.directory.in=.directory)
@INTLTOOL_DIRECTORY_RULE@

EXTRA_DIST = $(directory_in_files) $(directory_DATA)

DISTCLEANFILES = $(directory_DATA)
