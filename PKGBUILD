# Contributor: chiku <chirantan DOT mitra AT gmail DOT com>

pkgname=modpoll
pkgver=3.4
pkgrel=2
pkgdesc='free modbus testing tool based on fieldtalk driver'
url='http://www.modbusdriver.com/modpoll.html'
arch=('i686' 'x86_64')
license=('other')
depends=()
makedepends=()
source=("http://www.modbusdriver.com/downloads/$pkgname.$pkgver.zip")
md5sums=('af5953808212e005b458ca90d7cf868b')


package() {
    install -d -m755 "$pkgdir/usr/bin/"
    cd $srcdir/linux
    install -m 755 $pkgname "$pkgdir/usr/bin/"
}
