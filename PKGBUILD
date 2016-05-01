pkgname=gdrive
pkgver=2.1.0
pkgrel=1
pkgdesc="Command line utility for uploading and downloading single files to your Google Drive"
arch=('x86_64')
url="https://github.com/prasmussen/gdrive"
license=('MIT')
source=("$pkgname::https://docs.google.com/uc?id=0B3X9GlR6EmbnQ0FtZmJJUXEyRTA&export=download")
md5sums=('a4939147618bf3c75dc82595cb429e1d')
package() {
    install -dm755 "$pkgdir/usr/bin"
    install -m755 "$srcdir/$pkgname" "$pkgdir/usr/bin/$pkgname"
}
