DIR=	${DATADIR}/support/init.d.examples
INC=	README.md
SRCS=	avahi-dnsconfd.in avahid.in dhcpcd.in dbus.in \
	hald.in named.in ntpd.in \
	openvpn.in polkitd.in sshd.in wpa_supplicant.in
BIN=	${OBJS}

MK=	../../mk

SED_EXTRA+= -e 's:@VARBASE@:/var:g'

include ${MK}/os.mk
include ${MK}/scripts.mk
