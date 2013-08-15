pkgname=thinkwatt
pkgver=0.4
pkgrel=0
pkgdesc="record power consumption, calculate the average and create a gnuplot graphic"
arch=('any')
url="https://github.com/Bzzz/thinkwatt"
license=('GPL')
depends=('gawk' 'sed')
optdepends=('gnuplot' 'tp_smapi')
source=(https://github.com/Bzzz/thinkwatt/raw/master/thinkwatt)

build() {
  install -d	${pkgdir}/usr/bin
  install -m755 ${srcdir}/${pkgname} ${pkgdir}/usr/bin/
  ln -s /usr/bin/${pkgname} ${pkgdir}/usr/bin/twatt
}
md5sums=('879b1e03646b3000f2d638f26db8eb37')
