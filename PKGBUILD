#Maintainer: Nicolas Cisco <ncis20@gmail.com>

_pkgname='Apricity Themes'
pkgname=apricity-themes-gnome
pkgver=1.1.0
pkgrel=1
pkgdesc='Gnome theme for Apricity OS'
arch=(any)
license=(GPL)
url="https://github.com/nickcis/apricity-themes-gnome"
depends=()
replaces=(apricity-themes)
conflicts=(apricity-themes apricity-themes-cinnamon)
provides=(apricity-themes)
source=("git+https://github.com/nickcis/apricity-themes-gnome#branch=master")
sha256sums=('SKIP')
install="apricity-themes-gnome.install"

package() {
	rm -rf "${pkgdir}/usr/share/themes/Arctic Apricity"
	mkdir -p "${pkgdir}/usr/share/themes"
	# mkdir -p "${pkgdir}/etc/skel/.config/autostart"
	#mkdir -p "${pkgdir}/usr/share/gnome-shell/extensions"
	#cp -rf ${srcdir}/apricity-themes-gnome/extensions/* "${pkgdir}/usr/share/gnome-shell/extensions"
	cp -rf "${srcdir}/apricity-themes-gnome/Arctic Apricity" "${pkgdir}/usr/share/themes"
	# cp -f "${srcdir}/apricity-themes-gnome/firstrun-desktop.sh" "${pkgdir}/etc/skel/.config/autostart"
}
