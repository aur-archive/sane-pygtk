# Contributor: Lex Black <autumn-wind at web dot de>
# Contributor: Allan McRae <mcrae_allan@hotmail.com>

pkgname=sane-pygtk
pkgver=0.1.1
pkgrel=1
pkgdesc="SANE graphical front end"
arch=(i686 x86_64)
url="http://sane-pygtk.sourceforge.net/"
license=('unknown')
depends=('python-imaging' 'sane')
source=(http://downloads.sourceforge.net/${pkgname}/${pkgname}-${pkgver}.tar.gz)
md5sums=('6ef915264c4b98eb395f2659c42f0191')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  python2 setup.py install --root="$pkgdir"
}
