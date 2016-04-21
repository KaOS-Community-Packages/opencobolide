pkgname=opencobolide
pkgver=4.7.3
pkgrel=1
pkgdesc="A simple and lightweight COBOL IDE based on the GnuCOBOL compiler."
arch=("x86_64")
url="https://github.com/OpenCobolIDE/OpenCobolIDE"
license=("GPL")
depends=("python3" "pyqt5-python3" "gnu-cobol")
makedepends=("python3-setuptools")
source=("https://launchpad.net/cobcide/4.0/${pkgver}/+download/OpenCobolIDE-${pkgver}.tar.gz")
md5sums=('25a4705ee07261e6b89095447aa6f4eb')

package() {
  cd "$srcdir/OpenCobolIDE-$pkgver"
  python3 setup.py install --root="$pkgdir/" --optimize=1
}
