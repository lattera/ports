# Created by: Ruan Wei (iamayan@gmail.com)
# $FreeBSD$

PORTNAME=	skyeye
PORTVERSION=	1.2.5
PORTREVISION=	1
DISTVERSIONSUFFIX=	_REL
CATEGORIES=	emulators
MASTER_SITES=	SF/${PORTNAME}/${PORTNAME}/${PORTNAME}-${PORTVERSION}

MAINTAINER=	ports@FreeBSD.org
COMMENT=	Environment simulates typical ARM-base embedded computer systems

LICENSE=	GPLv2

USE_BINUTILS=	yes
USE_GCC=	any
GNU_CONFIGURE=	yes
CONFIGURE_ENV=	ac_cv_func_working_mktime=yes

NOPIE_PORTS=	yes
NORELRO_PORTS=	yes

PLIST_FILES=	bin/skyeye

.include <bsd.port.mk>
