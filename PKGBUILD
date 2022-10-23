# Maintainer:  echo -n 'TWljaGFsIFMuIDxtaWNoYWxAZ2V0Y3J5c3QuYWw+' | base64 -d
# Contributor: echo -n 'cmNhbmRhdUBnZXRjcnlzdC5hbA=='             | base64 -d
# Contributor: echo -n 'amFzaW8gPGphc2lvQGdldGNyeXN0LmFsPg=='     | base64 -d

pkgname=crystal-wallpapers
_pkgname=wallpapers
pkgver=1.0.3
pkgrel=3
pkgdesc='Crystal Linux Wallpapers'
arch=('any')
url="https://github.com/crystal-linux/${_pkgname}"
license=('GPL')
source=("${pkgname}-${pkgver}::${url}/archive/v${pkgver}.tar.gz")
sha256sums=('3d2fed68b505606ba2f7f5d6361692d8dd1e2017bf1dbcee939f1e77d9ef771e')

package() {
    cd "${srcdir}/${_pkgname}-${pkgver}"
    install -d "${pkgdir}/usr/share/backgrounds/crystal/"
    install -Dm 644 *.png "${pkgdir}/usr/share/backgrounds/crystal/"
    install -Dm 644 *.svg "${pkgdir}/usr/share/backgrounds/crystal/"
    install -Dm 644 crystal-backgrounds.yml "${pkgdir}/usr/share/gnome-background-properties/crystal-backgrounds.xml"
}
