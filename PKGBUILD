# Maintainer: Daniel Hillenbrand <codeworkx@bbqlinux.org>

pkgname=bbqlinux-livemedia
pkgver=0.0.4
pkgrel=1
pkgdesc="Tools for the BBQLinux live media"
arch=('any')
url="https://github.com/bbqlinux/bbqlinux-livemedia"
license=('GPL')
depends=('python2' 'qt4' 'python2-pyqt')

package() {
  cd "$pkgdir"

  install -Dm755 "$srcdir/usr/bin/bbqlinux-greeter" usr/bin/bbqlinux-greeter
  
  cp -R "$srcdir/etc" etc
  cp -R "$srcdir/usr/lib" usr/lib
  cp -R "$srcdir/usr/share" usr/share
  
}
