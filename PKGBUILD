# Maintainer: Your Name <your@email>
pkgname=passpony
pkgver=1.0.0
pkgrel=1
pkgdesc="Cute and secure Diceware-style passphrase generator"
arch=('any')
url="https://github.com/symphonic-navigator/passpony"
license=('GPL3')
depends=('python') # or whatever your implementation needs
source=("$pkgname-$pkgver.tar.gz")
sha256sums=('SKIP')  # Replace with actual checksum if uploading source

package() {
  cd "$srcdir/$pkgname-$pkgver"
  install -Dm755 passpony.py "$pkgdir/usr/bin/passpony"
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
  install -Dm644 README.md "$pkgdir/usr/share/doc/$pkgname/README.md"
}
