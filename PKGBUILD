# Maintainer: Matt C <mdc028[at]bucknell[dot]edu>

_name=wallpapers

pkgname="crystal-$_name"
pkgver=1.0.3
pkgrel=2
pkgdesc="Crystal Linux Wallpaper Images"
arch=('any')
url="https://github.com/crystal-linux/$_name"
license=('GPL')
source=("git+$url")
depends=()
conflicts=()
sha256sums=('SKIP')

package() {
    cd "${srcdir}/${_name}"

    mkdir -p "${pkgdir}/usr/share/backgrounds/crystal"
    cp -rv *.png *.svg "${pkgdir}/usr/share/backgrounds/crystal/."
}
