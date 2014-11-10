all: install

install: /etc/init.d/tightvncserver

/etc/init.d/tightvncserver: tightvncserver
	cp $< $@
	chmod +x $@
	insserv /etc/init.d/tightvncserver
