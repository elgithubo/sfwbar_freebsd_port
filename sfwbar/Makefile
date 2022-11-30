PORTNAME=	sfwbar
DISTVERSION=	v1.0_beta9
CATEGORIES=	x11

MAINTAINER=	elfreebsdo@e.mail.de
COMMENT=	Flexible taskbar application for wayland compositors
WWW=		https://github.com/LBCrion/sfwbar

LICENSE=	GPLv3

USES=	meson ninja

USE_GITHUB=	yes
GH_ACCOUNT=	LBCrion

LIB_DEPENDS+=libgtk-3.so:x11-toolkits/gtk30
LIB_DEPENDS+=libcairo.so:graphics/cairo
LIB_DEPENDS+=libcairo.so:graphics/cairo
LIB_DEPENDS+=libgdk_pixbuf-2.0.so:graphics/gdk-pixbuf2
LIB_DEPENDS+=libgio-2.0.so:devel/glib20
LIB_DEPENDS+=libgobject-2.0.so:devel/glib20
LIB_DEPENDS+=libglib-2.0.so:devel/glib20

LIB_DEPENDS+=libgtk-layer-shell.so:x11-toolkits/gtk-layer-shell
LIB_DEPENDS+=libwayland-client.so:graphics/wayland
LIB_DEPENDS+=libjson-c.so:devel/json-c

.include <bsd.port.mk>
