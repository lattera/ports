# $FreeBSD$

PORTNAME=	tesla
DISTVERSION=	0.0.20140425
PORTREVISION=	1
CATEGORIES=	devel lang

MAINTAINER=	brooks@FreeBSD.org
COMMENT=	Temporally Enhanced Security Logic Assertions

USES=		cmake:outsource execinfo ninja

NOPIE_PORTS=	yes
NORELRO_PORTS=	yes

BUILD_DEPENDS=	clang33:lang/clang33
RUN_DEPENDS=	clang33:lang/clang33
LIB_DEPENDS=	libprotobuf.so:devel/protobuf

USE_GITHUB=	yes
GH_ACCOUNT=	CTSRD-TESLA
GH_PROJECT=	TESLA
GH_TAGNAME=	3136f0f

CC=		clang33
CXX=		clang++33

CMAKE_ARGS+=	-DCMAKE_LLVM_CONFIG=llvm-config33

BROKEN_FreeBSD_9=	does not build

.include <bsd.port.mk>
