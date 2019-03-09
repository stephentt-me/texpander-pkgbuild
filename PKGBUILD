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
source=("${pkgname}::git+https://github.com/leehblue/texpander")
md5sums=("SKIP")

package() {
    cd ${pkgname}
    install -Dm755 texpander.sh ${pkgdir}/usr/bin/texpander
}