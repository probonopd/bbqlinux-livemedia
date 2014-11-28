# Maintainer: Daniel Hillenbrand <codeworkx [at] bbqlinux [dot] org>

pkgname=bbqlinux-livemedia
pkgver=1.3.0
pkgrel=1
pkgdesc="Configuration of the BBQLinux live media"
arch=('any')
url="https://github.com/bbqlinux/bbqlinux-livemedia"
license=('GPL')
depends=('python2' 'qt4' 'python2-pyqt')

package() {
  cd "$pkgdir"

  install -Dm755 "$srcdir/usr/bin/bbqlinux-greeter" usr/bin/bbqlinux-greeter
  install -Dm755 "$srcdir/usr/bin/bbqlinux-livemedia-userconf" usr/bin/bbqlinux-livemedia-userconf
  install -Dm755 "$srcdir/usr/bin/prepare_livesystem" usr/bin/prepare_livesystem
  
  cp -R "$srcdir/etc" etc
  cp -R "$srcdir/usr/lib" usr/lib
  cp -R "$srcdir/usr/share" usr/share
  
}
