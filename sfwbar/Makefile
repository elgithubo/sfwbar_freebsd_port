PORTNAME=	sfwbar
DISTVERSION=	v1.0_beta9
CATEGORIES=	x11

MAINTAINER=	tino.engel@mail.de
COMMENT=	Flexible taskbar application for wayland compositors
WWW=		https://github.com/LBCrion/sfwbar

LICENSE=	GPLv3

BUILD_DEPENDS=	wayland-protocols>0:graphics/wayland-protocols
LIB_DEPENDS=	libgtk-3.so:x11-toolkits/gtk30 \
		libcairo.so:graphics/cairo \
		libcairo.so:graphics/cairo \
		libgdk_pixbuf-2.0.so:graphics/gdk-pixbuf2 \
		libgio-2.0.so:devel/glib20 \
		libgobject-2.0.so:devel/glib20 \
		libglib-2.0.so:devel/glib20 \
		libgtk-layer-shell.so:x11-toolkits/gtk-layer-shell \
		libwayland-client.so:graphics/wayland \
		libjson-c.so:devel/json-c
RUN_DEPENDS=	wayland-protocols>0:graphics/wayland-protocols

USES=	meson ninja pkgconfig

USE_GITHUB=	yes
GH_ACCOUNT=	LBCrion

SUB_FILES=	pkg-message
SUB_LIST=	DATADIR=${DATADIR}

.include <bsd.port.mk>
