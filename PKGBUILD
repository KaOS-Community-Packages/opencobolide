pkgname=opencobolide
pkgver=4.7.5
pkgrel=1
pkgdesc="A simple and lightweight COBOL IDE based on the GnuCOBOL compiler."
arch=("x86_64")
url="https://github.com/OpenCobolIDE/OpenCobolIDE"
license=("GPL")
depends=("python3" "pyqt5-python3" "gnu-cobol")
makedepends=("python3-setuptools")
source=("https://launchpad.net/cobcide/4.0/${pkgver}/+download/OpenCobolIDE-${pkgver}.tar.gz")
md5sums=('f2e7bf352f5806a9c0a4de1de0aef03b')


package() {
  cd "$srcdir/OpenCobolIDE-$pkgver"
  python3 setup.py install --root="$pkgdir/" --optimize=1
}
