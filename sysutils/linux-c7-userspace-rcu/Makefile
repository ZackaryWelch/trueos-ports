# Created by: David Naylor <dbn@FreeBSD.org>
# $FreeBSD$

PORTNAME=	userspace-rcu
PORTVERSION=	0.7.16
CATEGORIES=	sysutils linux
MASTER_SITES=	EPEL7/u

MAINTAINER=	emulation@FreeBSD.org
COMMENT=	Userspace read-copy-update (RCU) data synchronization library (CentOS ${LINUX_DIST_VER})

DESCR=		${.CURDIR}/../liburcu/pkg-descr
ONLY_FOR_ARCHS=	amd64
RPMVERSION=	1.el7
USES=		linux:c7
USE_LDCONFIG=	yes
USE_LINUX_RPM=	yes

OPTIONS_DEFINE=	DOCS

.include <bsd.port.mk>
