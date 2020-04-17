#Maintainer: Vladimir Yerilov <openmindead at gmail dot com>

pkgname=plymouth-theme-bgrt-mi
pkgver=1.4
pkgrel=1
pkgdesc="A Plymouth theme based on BGRT & Spinner themes, but featuring Xiaomi progress bar."
arch=('any')
url="https://github.com/openmindead/plymouth-theme-bgrt-mi"
license=('GPL')
depends=('plymouth')

install='plymouth-theme-bgrt-mi.install'
source=("plymouth-theme-bgrt-mi-${pkgver}.tar.gz::https://github.com/openmindead/plymouth-theme-bgrt-mi/archive/${pkgver}.tar.gz"
        'plymouth-theme-bgrt-mi.install')
md5sums=('ad45fa28678e5231928ef906639b3e9d'
         'f63de992eb1cc2a4d794c1c91b34bbf0')

package() {
    cd $srcdir/${pkgname}-${pkgver}
    mkdir -p $pkgdir/usr/share/plymouth/themes/bgrt-mi
    install -Dm644 * "${pkgdir}"/usr/share/plymouth/themes/bgrt-mi
} 
