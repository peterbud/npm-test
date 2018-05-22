_realname=test
pkgbase=mingw-w64-${_realname}
pkgname=("${MINGW_PACKAGE_PREFIX}-${_realname}")
pkgver=1.0
pkgrel=1
pkgdesc="Test PKGBUILD"
arch=('any')
url="https://github.com/whatever/x"
license=('BSD')

makedepends=(
            "${MINGW_PACKAGE_PREFIX}-nodejs"
             )

source=("package.json")
sha256sums=('23907caba858498626710d79e6ec1d8777611a641f40c4afcf464162fca165c8')

#optdepends=('pandoc: notebook export')

prepare() {  
  cd "$srcdir"/

}

build() {

  cd "$srcdir/"

  npm install

  echo "FINISHED BUILD"
}

package() {

  cd "$srcdir/"

  echo "FINISHED PACKAGE"
}
