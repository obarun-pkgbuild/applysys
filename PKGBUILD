# Maintainer Eric Vidal <eric@obarun.org>

pkgname=applysys
pkgver=0.1
pkgrel=1
pkgdesc='A scripts to parse and apply sysusers.d files'
url='https://github.com/Obarun/applysys.git'
arch=(x86_64)
license=(ISC)
groups=(base)
depends=('bash' 'pacman' 'obarun-libs' 'shadow' 'glibc')
makedepends=('git')
sha1sums=('SKIP')
source=("${pkgname}::git+${url}#tag=v${pkgver}")
validpgpkeys=('6DD4217456569BA711566AC7F06E8FDE7B45DAAC') # Eric Vidal

package() {

  cd "$pkgname"
		 
  make DESTDIR="$pkgdir" install
}
