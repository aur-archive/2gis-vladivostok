# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-vladivostok
pkgver=28
pkgrel=1
pkgdesc="Map of Vladivostok for 2GIS, July 2012"
arch=('i686' 'x86_64')
url="http://vladivostok.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.6.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Vladivostok-28.orig.zip")
md5sums=('935d575f366adc650f418bb455086faa')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Vladivostok.dgdat "${startdir}/pkg/opt/2gis/vladivostok.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Vladivostok.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Vladivostok.dglf" || return 1
     
}

