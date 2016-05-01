pkgname=gdrive
pkgver=2.0.1
pkgrel=1
pkgdesc="Command line utility for uploading and downloading single files to your Google Drive"
arch=('x86_64')
url="https://github.com/prasmussen/gdrive"
license=('MIT')
source=("$pkgname::https://drive.google.com/uc?id=0B3X9GlR6EmbnWksyTEtCM0VfaFE")
sha256sums=('ae1e3f522e1e273029324bbb2cb34c0ffdbd5d8f131090e4eed9053f52f9d546')

package() {
    install -dm755 "$pkgdir/usr/bin"
    install -m755 "$srcdir/$pkgname" "$pkgdir/usr/bin/$pkgname"
}
