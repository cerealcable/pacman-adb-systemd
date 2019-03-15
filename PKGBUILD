# Maintainer: Morgan Humes <morgan@lanaddict.com>
pkgname=adb-systemd
pkgver=0.0.1
pkgrel=1
pkgdesc="Android Debug Server Systemd Service"
arch=(any)
url="https://developer.android.com/studio/command-line/adb"
license=('GPL')
depends=(android-tools)
install=$pkgname.install

package() {
    install -Dm644 ${srcdir}/adb.service ${pkgdir}/usr/lib/systemd/system/adb.service
}
