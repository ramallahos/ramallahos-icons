# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-icons
pkgver=1
pkgrel=1
pkgdesc="Wallpapers for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('MIT')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd ${pkgname}
    install -d "${pkgdir}/usr/share/icons/$pkgname"
    cp -r src/$pkgname/* "${pkgdir}/usr/share/icons/"

}

