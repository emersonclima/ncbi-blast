# Maintainer: Emerson C. Lima <emersoncflima at gmail com>
pkgname=("ncbi-blast")
pkgver=2.6.0
pkgrel=1
epoch=
pkgdesc="BLAST Command Line Applications"
arch=("x86_64")
url="https://blast.ncbi.nlm.nih.gov/Blast.cgi"
license=('LGPL2.1')
groups=()
depends=("perl" "zlib" "libidn")
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("ftp://ftp.ncbi.nih.gov/blast/executables/blast+/$pkgver/ncbi-blast-$pkgver+-x64-linux.tar.gz")
noextract=()
md5sums=("681b6ecf8d1d08b63f5f940fb53bd6e8")
validpgpkeys=()

package() {
	cd "ncbi-blast-$pkgver+"
	install -d $pkgdir/usr/bin 
	install bin/* $pkgdir/usr/bin 
}
