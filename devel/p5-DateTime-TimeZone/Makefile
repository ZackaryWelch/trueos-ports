# Created by: mat
# $FreeBSD$

PORTNAME=	DateTime-TimeZone
PORTVERSION=	2.13
PORTEPOCH=	1
CATEGORIES=	devel perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	jadawin@FreeBSD.org
COMMENT=	Time zone object base class and factory

LICENSE=	ART10 GPLv1+
LICENSE_COMB=	dual
LICENSE_FILE=	${WRKSRC}/LICENSE

BUILD_DEPENDS=	p5-Class-Singleton>=1.03:devel/p5-Class-Singleton \
		p5-Module-Runtime>=0:devel/p5-Module-Runtime \
		p5-Params-ValidationCompiler>=0.13:devel/p5-Params-ValidationCompiler \
		p5-Try-Tiny>=0:lang/p5-Try-Tiny \
		p5-namespace-autoclean>=0:devel/p5-namespace-autoclean
RUN_DEPENDS:=	${BUILD_DEPENDS}
TEST_DEPENDS=	p5-Test-Output>0:devel/p5-Test-Output \
		p5-Test-Requires>0:devel/p5-Test-Requires \
		p5-Test-Fatal>0:devel/p5-Test-Fatal

NO_ARCH=	yes
USES=		perl5
USE_PERL5=	configure

.include <bsd.port.mk>
