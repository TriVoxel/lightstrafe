# Maintainer: Keegan Milsten <willnhalt@gmail.com>

pkgname="lightstrafe"
_pkgname="lightstrafe"
pkgver=1.0
pkgrel=1.0
pkgdesc='A fun 3D shooting platformer game created by Caden Mitchell'

CHANGE TO YOUR REPO ON GITHUB!!!!!!!!!!url='https://github.com/keeganmilsten/Reborn-Packages/tree/master/deepin-file-manager-root'

arch=('any')
license=('GPL3')
depends=('libpng' 'libtiff' 'openexr' 'python' 'desktop-file-utils' 'python-requests' 'shared-mime-info' 'xdg-utils' 'hicolor-icon-theme' 'glew' 'openjpg' 'python-numpy' 'freetype2' 'openal' 'ffmpeg' 'fftw' 'boost-libs' 'opencollada' 'alembic' 'openimageio' 'libsndfile' 'jack' 'opencolorio' 'jemalloc' 'libspnav' 'plex' 'openvdb' 'log4cplus' 'sdl2')

CHANGE!!!!!!!!!source=("${pkgname}-${pkgver}.tar.gz::https://codeload.github.com/keeganmilsten/${_pkgname}/tar.gz/1.1")

package() {
    cd "${srcdir}/${_pkgname}-1.0"

    install -D -m 777 lightstrafe \
    	 "${pkgdir}/usr/bin/lightstrafe"

    install -D -m 755 lightstrafe.desktop \
    	 "${pkgdir}/usr/share/applications/lightstrafe.desktop"

    install -D -m 755 ligthstrafe.png \
    	 "${pkgdir}/usr/share/icons/lightstrafe.png"
}
