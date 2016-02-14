pkgname=opencobolide
pkgver=4.7.2
pkgrel=1
pkgdesc="A simple and lightweight COBOL IDE based on the GnuCOBOL compiler."
arch=("x86_64")
url="https://github.com/OpenCobolIDE/OpenCobolIDE"
license=("GPL")
depends=("python3" "pyqt5-python3" "gnu-cobol")
makedepends=("python3-setuptools")
source=("https://github.com/OpenCobolIDE/OpenCobolIDE/archive/${pkgver}.tar.gz")
md5sums=('08c0f74b977a37c158e7b8a17f0735e9')

package() {
  cd "$srcdir/OpenCobolIDE-$pkgver"
  python3 setup.py install --root="$pkgdir/" --optimize=1
}
