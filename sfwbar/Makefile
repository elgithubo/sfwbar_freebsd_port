PORTNAME=	sfwbar
DISTVERSION=	v1.0_beta9
CATEGORIES=	x11
USE_GITHUB=     yes
GH_ACCOUNT=     LBCrion

LICENSE=	GPLv3

MAINTAINER=	elfreebsdo@e.mail.de
COMMENT=	A flexible taskbar application for wayland compositors
WWW=		https://github.com/LBCrion/sfwbar

LIB_DEPENDS+=libgtk-3.so.0:x11-toolkits/gtk30 
LIB_DEPENDS+=libcairo.so.2:graphics/cairo 
LIB_DEPENDS+=libcairo.so.2:graphics/cairo 
LIB_DEPENDS+=libgdk_pixbuf-2.0.so.0:graphics/gdk-pixbuf2 
LIB_DEPENDS+=libgio-2.0.so.0:devel/glib20
LIB_DEPENDS+=libgobject-2.0.so.0:devel/glib20 
LIB_DEPENDS+=libglib-2.0.so.0:devel/glib20 

LIB_DEPENDS+=libgtk-layer-shell.so:x11-toolkits/gtk-layer-shell
LIB_DEPENDS+=libwayland-client.so:graphics/wayland
LIB_DEPENDS+=libjson-c.so:devel/json-c

USES= meson ninja

.include <bsd.port.mk>