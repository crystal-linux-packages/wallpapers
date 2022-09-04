# Maintainer:  echo -n 'TWljaGFsIFMuIDxtaWNoYWxAZ2V0Y3J5c3QuYWw+' | base64 -d
# Contributor: echo -n 'amFzaW8gPGphc2lvQGdldGNyeXN0LmFsPg=='     | base64 -d

_name=wallpapers

pkgname="crystal-$_name"
pkgver=1.0.3
pkgrel=2
pkgdesc='Crystal Linux Wallpapers'
arch=('any')
url="https://github.com/crystal-linux/$_name"
license=('GPL')
source=("git+$url")
makedepends=('git')
sha256sums=('SKIP')

package() {
    cd "$srcdir/$_name"

    install -Dm 0755 *.png *.svg "$pkgdir/usr/share/backgrounds/crystal/."
}
