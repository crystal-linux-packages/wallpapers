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
    install -Dm 644 "crystal-blob light.png" "${pkgdir}/usr/share/backgrounds/crystal/crystal-blob light.png"
    install -Dm 644 crystal-waves-horizontal.png "${pkgdir}/usr/share/backgrounds/crystal/crystal-waves-horizontal.png"
    install -Dm 644 crystal-waves-vertical.png "${pkgdir}/usr/share/backgrounds/crystal/crystal-waves-vertical.png"
    install -Dm 644 gaypaper.png "${pkgdir}/usr/share/backgrounds/crystal/gaypaper.png"
    install -Dm 644 "crystal-blob light.svg" "${pkgdir}/usr/share/backgrounds/crystal/crystal-blob light.svg"
    install -Dm 644 crystal-blob.svg "${pkgdir}/usr/share/backgrounds/crystal/crystal-blob.svg"
    install -Dm 644 gaypaper.svg "${pkgdir}/usr/share/backgrounds/crystal/gaypaper.svg"
}
