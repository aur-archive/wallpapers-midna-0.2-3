
# Maintainer: xphnx <xphnx@riseup.net>

pkgname=wallpapers-midna-0.2-3
pkgver=0.2
pkgrel=3
pkgdesc="Litho Flowers themed wallpaper"
arch=('i686' 'x86_64')
url="http://kaosx.us"
license=('GPL')
groups=('kde' 'kde-uninstall')
#depends=('kdebase-workspace')
#conflicts=('')
source=('http://kaosx.us/repo/apps/wallpapers-midna-0.2-3-x86_64.pkg.tar.xz')
md5sums=('e86ea90fb62cb3cfcf85ccd741d63954')

package() {
  cd $srcdir
  mkdir -p $pkgdir/usr/share/wallpapers/midna
  cp -R ./usr/share/wallpapers/midna $pkgdir/usr/share/wallpapers
  # fix file rights
  chmod 755 -R $pkgdir/usr/share/wallpapers/midna
}  
