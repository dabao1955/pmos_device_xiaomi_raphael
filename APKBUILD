# Reference: <https://postmarketos.org/devicepkg>
pkgname=device-xiaomi-raphael
pkgdesc="Xiaomi Redmi K20 Pro"
pkgver=0.1
pkgrel=0
url="https://postmarketos.org"
license="MIT"
arch="aarch64"
options="!check !archcheck"
depends="
	linux-xiaomi-raphael
	mkbootimg
	postmarketos-base
"
makedepends="devicepkg-dev"
source="deviceinfo"

build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="(run 'pmbootstrap checksum device-xiaomi-raphael' to fill)"
