pkgname=2gis-vladivostok
pkgver=54
pkgrel=1
pkgdesc="Map of Vladivostok for 2GIS, September 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/vladivostok/products/download#linux"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.com/arhives/2GISData_Vladivostok-54.orig.zip")
md5sums=('740752e72050c64eeb66d8a2237a19a2')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Vladivostok.dgdat" "${pkgdir}/opt/2gis/2gis-vladivostok.dgdat" || return 1
  
}
