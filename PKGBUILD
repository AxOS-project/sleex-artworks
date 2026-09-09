pkgname="sleex-artworks"
pkgver="1.0"
pkgrel="2"
pkgdesc="Icons and wallpapers for Sleex desktop environment"
arch=("x86_64")

package(){
   mkdir -p ${pkgdir}/usr/share/pixmaps/sleex
   cp -r ${srcdir}/logo/* ${pkgdir}/usr/share/pixmaps/sleex

   mkdir -p ${pkgdir}/usr/share/backgrounds/sleex
   cp -r ${srcdir}/wallpapers/* ${pkgdir}/usr/share/backgrounds/sleex/
}
