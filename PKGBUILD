# Maintainer: Baumi Baum <spam@j-baum.at>

pkgname=snowdrop-gnome-schema-override
pkgver=1
pkgrel=0
pkgdesc="Overrides some default Gnome settings"
arch=('any')
license=('GPL3')
makedepends=('git')
depends=('snowdrop-backgrounds')
options=(!strip !emptydirs)
source=("git+https://github.com/womba/snowdrop-gnome-schema-override")
sha256sums=('SKIP')

package() {
  cd "$pkgname"
  mkdir -p "$pkgdir/usr/share/glib-2.0/schemas/"
  cp org.snowdrop.gnome.schema.override "$pkgdir/usr/share/glib-2.0/schemas/"
}

