# Created by: Joe Maloney <jmaloney@ixsystems.com>
# $FreeBSD$

PORTNAME=	ixautomation
PORTVERSION=	18.06
CATEGORIES=	sysutils
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	jmaloney@ixsystems.com
COMMENT=	Automation framework for iXsystems projects

LICENSE=	BSD2CLAUSE

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}pip>0:devel/py-pip@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}pytest>=0:devel/py-pytest@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}requests>=0:www/py-requests@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}selenium>=0:www/py-selenium@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}ws4py>=0:www/py-ws4py@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}unittest-xml-reporting>=0:devel/py-unittest-xml-reporting@${PY_FLAVOR} \
		ix-bhyve>=0:sysutils/ix-bhyve \
		${LOCALBASE}/bin/expect:lang/expect \
		${LOCALBASE}/bin/sshpass:security/sshpass \
		bhyve-firmware>=0:sysutils/bhyve-firmware

WRKSRC_SUBDIR=  src
USES=		python:3.6
USE_PYTHON=	distutils
MAKE_ARGS=	PREFIX=${STAGEDIR}${PREFIX}

USE_GITHUB=	yes
GH_ACCOUNT=	ixsystems
GH_PROJECT=	ixautomation
GH_TAGNAME=	b2f9f54d754ea52616cdd16d5b8bcd630e772b55

.include <bsd.port.mk>
