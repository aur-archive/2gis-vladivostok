pkgname=2gis-vladivostok
pkgver=38
pkgrel=2
pkgdesc="Map of Vladivostok for 2GIS, May 2013"
arch=('i686' 'x86_64')
url="http://vladivostok.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.5.1')
source=("http://download.2gis.ru/arhives/2GISData_Vladivostok-38.orig.zip")
md5sums=('a7b58d6694a9eb34c848c307f85fb196')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Vladivostok.dgdat" "${pkgdir}/opt/2gis/vladivostok.dgdat" || return 1
  install -D -m 644 "${srcdir}/2gis/3.0/Plugins/DGisLan/Vladivostok.dglf" "${pkgdir}/opt/2gis/Plugins/DGisLan/vladivostok.dglf" || return 1
}
