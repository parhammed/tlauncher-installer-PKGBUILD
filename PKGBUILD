# Maintainer: Parham Taki <parhammed@gmail.com>

pkgname=tlauncher
pkgver=1
pkgrel=1
pkgdesc="TLAUNCHER – THE BEST MINECRAFT LAUNCHER"
arch=('any')
url="TLAUNCHER – THE BEST MINECRAFT LAUNCHER"
license=('custom:tlauncher')
depends=()
optdepends=()
options=(!debug)
source=("tlauncher-linux-installer.deb::https://dl2.tlauncher.org/f.php?f=files%2Ftlauncher-linux-installer.deb")
sha512sums=('0e12c389e7e1a30ab48470106338b926ad548953d5e03eb5d5a86e77eb530d37e8d483751cfef0f7607a996a3809a1f234e805147af29615782872331aa1ab61')

package() {
        bsdtar -xf data.tar.xz -C "$pkgdir/"
}
