# Maintainer: marshmallow <marshycity@gmail.com>
#
# This PKGBUILD was generated by `cargo aur`: https://crates.io/crates/cargo-aur

pkgname=gh-cal-bin
pkgver=0.1.3
pkgrel=1
pkgdesc="View your github contribution calander in unicode"
url="https://github.com/mrshmllow/gh-cal"
license=("MIT")
arch=("x86_64")
provides=("gh-cal")
conflicts=("gh-cal")
source=("https://github.com/mrshmllow/gh-cal/releases/download/v$pkgver/gh-cal-$pkgver-x86_64.tar.gz")
sha256sums=("0bd0435112780c56ac40719cb56b9c0b81e1502ec59d9b5ca021c9b2221ef414")

package() {
    install -Dm755 gh-cal -t "$pkgdir/usr/bin"
    install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
