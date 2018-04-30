# Maintainer: Caden Mitchell <sidedvirus@outlook.com>

pkgname="lightstrafe"
_pkgname="lightstrafe"
pkgver=4.30.18
pkgrel=4.30.18
pkgdesc='A fun 3D shooting platformer game created by Caden Mitchell (SidedVirus)'
url='https://github.com/CadenMitchell/lightstrafe/'
arch=('any')
license=('GPL3')
depends=('libpng' 'libtiff' 'openexr' 'python' 'desktop-file-utils' 'python-requests' 'shared-mime-info' 'xdg-utils' 'hicolor-icon-theme' 'glew' 'python-numpy' 'freetype2' 'openal' 'ffmpeg' 'fftw' 'boost-libs' 'opencollada' 'alembic' 'openimageio' 'libsndfile' 'jack' 'opencolorio' 'jemalloc' 'libspnav' 'openvdb' 'log4cplus' 'sdl2')
source=("${pkgname}-${pkgver}.tar.gz::https://codeload.github.com/CadenMitchell/${_pkgname}/tar.gz/1.0")
package() {
    cd "${srcdir}/${_pkgname}-1.0"

    install -D -m 777 lightstrafe \
    	 "${pkgdir}/usr/bin/lightstfafe"

    install -D -m 755 lightstrafe.desktop \
    	 "${pkgdir}/usr/share/applications/lightstrafe.desktop"

    install -D -m 755 lightstrafe.png \
    	 "${pkgdir}/usr/share/icons/lightstrafe.png"
}
