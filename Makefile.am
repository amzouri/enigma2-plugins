ACLOCAL_AMFLAGS = -I m4

SUBDIRS = \
	aihdcontroler \
	antiscrollbar \
	audiosync \
	automaticcleanup \
	automatictimerlistcleanup \
	automaticvolumeadjustment \
	autoresolution \
	autotimer \
	babelzapper \
	bitrateviewer \
	bonjour \
	cdinfo \
	dreamirc \
	dreammediathek \
	dvdbackup \
	dyndns \
	easyinfo \
	easymedia \
	eibox \
	elektro \
	emailclient \
	epgrefresh \
	epgsearch \
	fancontrol2 \
	filebrowser \
	fritzcall \
	ftpbrowser \
	genuinedreambox \
	googlemaps \
	growlee \
	httpproxy \
	imdb \
	kiddytimer \
	lastfm \
	letterbox \
	logomanager \
	mediadownloader \
	menusort \
	merlinepg \
	merlinmusicplayer \
	meteoitalia \
	mosaic \
	moviecut \
	movielistpreview \
	movieretitle \
	moviesearch \
	movieselectionquickbutton \
	movietagger \
	movieepg \
	mphelp \
	multirc \
	mytube \
	namezap \
	ncidclient \
	netcaster \
	networkbrowser \
	ofdb \
	orfat \
	orfteletext \
	partnerbox \
	passwordchanger \
	permanentclock \
	pipzap \
	pluginhider \
	pluginsort \
	podcast \
	porncenter \
	quickbutton \
	reconstructapsc \
	remotetimer \
	rsdownloader \
	seekbar \
	serienfilm \
	setpasswd \
	shoutcast \
	showclock \
	simplerss \
	startupservice \
	startuptostandby \
	svdrp \
	tageditor \
	trafficinfo \
	tvcharts \
	unwetterinfo \
	valixdcontrol \
	virtualzap \
	vlcplayer \
	vps \
	weatherplugin \
	webcamviewer \
	webbouqueteditor \
	webinterface \
	werbezapper \
	youtubeplayer \
	yttrailer \
	zaphistorybrowser \
	zapstatistic \
	zdfmediathek

metadir = $(datadir)/meta
meta_DATA = index-enigma2-plugins.xml
CLEANFILES = index-enigma2-plugins.xml

index-enigma2-plugins.xml: $(top_srcdir)/genmetaindex.py $(top_srcdir)/*/meta/plugin_*.xml
	$(AM_V_GEN)$(PYTHON) $^ > $@
