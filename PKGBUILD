# Maintainer: Stephen Truong Trung Hieu <myemail at gmail dot com>
pkgname="texpander"
pkgdesc="A simple lightweight text expander written in bash."
url="https://github.com/leehblue/texpander"
pkgver="2.0"
pkgrel=1
arch=("any")
license=("GPL3")
depends=("xsel"
    "zenity"
    "xdotool")
_tag="cd53b183d147329ba5f5fc37abc8c671124217e9"
source=("${pkgname}-${_tag}.zip::https://github.com/leehblue/texpander/archive/${_tag}.zip")
sha1sums=("25302d3cd2b7e2bf7547aadc9872738fdeea6c16")

package() {
    cd ${pkgname}-${_tag}
    install -Dm755 texpander.sh ${pkgdir}/usr/bin/texpander
}