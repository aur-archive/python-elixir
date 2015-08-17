# Maintainer: Chris Brannon <chris@the-brannons.com>
# Contributor: Tomas A. Schertel <tschertel.at.gmail.com>
# Contributor: Lauri Jäntti <lauri.jantti@cs.joensuu.fi>
pkgname=python-elixir
pkgver=0.7.1
pkgrel=5
pkgdesc="A declarative layer on top of SQLAlchemy. It is a fairly thin wrapper, which provides the ability to define model objects following the Active Record design pattern"
url="http://elixir.ematia.de/"
license=('MIT')
arch=(any)
depends=('python2' 'python2-sqlalchemy' python2-distribute)
source=(http://pypi.python.org/packages/source/E/Elixir/Elixir-$pkgver.tar.gz)
md5sums=('5615ec9693e3a8e44f69623d58f54116')

build() {
  /bin/true
}

package() {
  cd "$srcdir/Elixir-$pkgver"
  python2 setup.py install --root="$pkgdir"
}
