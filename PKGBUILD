# Maintainer/Author: Alex Brown <code@alexpbrown.me>
pkgname=pkgcl
pkgver=0.3.0
pkgrel=1
pkgdesc="Get changelogs for Arch Linux packages"
arch=('any')
url="https://github.com/alexpbrown/arch-pkgcl"
license=('custom:WTFPL')
depends=("ruby" "ruby-nokogiri")
source=($pkgname "LICENSE")
md5sums=('d79466cb4c43c6705a3c5670317dbf43'
         '389a9e29629d1f05e115f8f05c283df5')

package() {
  cd "$srcdir"
  install -D -m644 LICENSE "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
  install -D $pkgname "${pkgdir}/usr/bin/${pkgname}"
}

# vim:set ts=2 sw=2 et:
