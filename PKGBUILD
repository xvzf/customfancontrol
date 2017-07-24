pkgname=customfancontrol
pkgdesc='Just my custom fan control...'
pkgver=0.1
pkgrel=3
arch=('x86_64')
url='https://github.com/xvzf/customfancontrol'
license=('GPL3')
depends=('smartmontools' 'hddtemp' 'lm_sensors' 'cronie')
provides=('customfancontrol')

package() {

  install -Dm755 ${srcdir}/customfancontrol ${pkgdir}/usr/bin/customfancontrol
  install -Dm655 ${srcdir}/customfancontrol.service ${pkgdir}/etc/systemd/system/customfancontrol.service

}
