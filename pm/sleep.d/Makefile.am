sleepdir = $(libdir)/pm-utils/sleep.d

sleep_SCRIPTS =			\
	00logging		\
	00powersave		\
	01grub			\
	49bluetooth		\
	55NetworkManager	\
	75modules		\
	90clock			\
	94cpufreq		\
	95led			\
	98video-quirk-db-handler \
	99video

EXTRA_DIST=$(sleep_SCRIPTS)

install-exec-local:
	-mkdir -p $(DESTDIR)$(sysconfdir)/pm/sleep.d

clean-local :
	rm -f *~
