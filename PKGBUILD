# Maintainer: BlackIkeEagle <ike DOT devolder AT gmail DOT com>

pkgname=csslint
_npmname=csslint
pkgver=0.10.0
pkgrel=2
pkgdesc="tool to help point out problems with your CSS code"
arch=('any')
makedepends=('npm')
depends=('nodejs')
url="https://github.com/stubbornella/csslint"
license=('MIT')
provides=('nodejs-csslint')

package() {
	local _npmdir="$pkgdir/usr/lib/node_modules/"
	mkdir -p $_npmdir
	cd $_npmdir
	npm install --user root -g --prefix "$pkgdir/usr" $_npmname@$pkgver
}
