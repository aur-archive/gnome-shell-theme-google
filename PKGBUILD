# Author:   plaidcounty <http://plaidcounty.deviantart.com/>
# Maintainer: sanderd17 <sanderd17 at gmail dot com>

pkgname=gnome-shell-theme-google
pkgver=1.5.1
pkgrel=3
pkgdesc="A Gnome-Shell theme by plaidcounty, based on the Google color schema." 
url="http://plaidcounty.deviantart.com/art/Google-Shell-259973461"
license=('GPLv3')
arch=('any')
depends=('gnome-shell>=3.2' 'ttf-droid')

makedepends=('unzip')
optdepends=(
	    'gnome-shell-extension-user-theme: User Theme extension for GNOME Shell'
            'gnome-tweak-tool: A tool to customize advanced GNOME 3 options.')
source=("http://www.deviantart.com/download/259973461/google_shell_by_plaidcounty-d4as4t1.zip")
md5sums=('81510b6e7d0fd7725a43c06dd2928e95')




build() {
  mkdir -p ${pkgdir}/usr/share/themes/
  mv ${srcdir}/ ${pkgdir}/usr/share/themes/Google-shell
}



