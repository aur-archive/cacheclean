# Contributor: graysky <graysky AT archlinux dot us>
# Contributer: alterkacker

pkgname=cacheclean
pkgver=2.1
pkgrel=5
pkgdesc='Cleans up pacman packages.  Users selects how many old versions to keep.'
arch=(any)
license=('GPLv3')
depends=('python')
source=("http://repo-ck.com/source/$pkgname/$pkgname-$pkgver.tar.xz")
sha256sums=('c4be2490689b5957a5f0e3cc65f7e4b8e74e4cdd70089514eba89d887db13481')
url=http://wiki.archlinux.org/index.php/CacheClean
install=readme.install

package() {
	cd "$pkgname-$pkgver"
	install -Dm755 $pkgname "$pkgdir/usr/bin/$pkgname"
}
