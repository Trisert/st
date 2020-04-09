pkgname=st-trisert-git
_pkgname=st
pkgver=0.8.2.r1062.2087ab9
pkgdesc="Simple terminal"
pkgrel=1
url='https://github.com/Trisert/st'
arch=('i686' 'x86_64')
license=('MIT')
options=('zipman')
depends=('libxft')
makedepends=('ncurses' 'libxext' 'git')
optdepends=('dmenu: feed urls to dmenu')
source=('git://github.com/Trisert/st')
md5sums=('SKIP')

provides=("${_pkgname}")
conflicts=("${_pkgname}")

package() {
        cd "${_pkgname}"
        make PREFIX=/usr DESTDIR="${pkgdir}" install
}
