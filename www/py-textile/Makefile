# Created by: Yi-Jheng Lin <yzlin@cs.nctu.edu.tw>
# $FreeBSD$

PORTNAME=	textile
PORTVERSION=	3.0.3
CATEGORIES=	www textproc python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	bofh@FreeBSD.org
COMMENT=	Textile markup generator written in Python

LICENSE=	BSD2CLAUSE

BUILD_DEPENDS=	${PYTHON_PKGNAMEPREFIX}pytest-runner>0:devel/py-pytest-runner@${FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}pytest>=2.8:devel/py-pytest@${FLAVOR}

USES=		python
USE_PYTHON=	distutils autoplist
NO_ARCH=	yes
USE_GITHUB=	yes
GH_ACCOUNT=	${PORTNAME}
GH_PROJECT=	python-${PORTNAME}

.include <bsd.port.mk>
