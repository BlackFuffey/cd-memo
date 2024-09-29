# Maintainer: BlackFuffey ethanthecomputerman@gmail.com
pkgname=cd-memo
pkgver=oct2024v1
pkgrel=1
pkgdesc="Enhanced cd that memorizes your working directory across sessions"
arch=('any')
url="https://github.com/BlackFuffey/cd-memo"
license=('MIT')
depends=('bash')
source=("cd-memo" "cd-memo-init" "README.md" "LICENSE")
sha256sums=(
    "39e1e8efd455c2e936c7a144d405310a0e04b531bc50ba21f2aa3d60b1730f51"  # cd-memo
    "f7488e88638d0127b11e3ce1ef4d27bfc963eb247aa35191e00afa8f5ed86dfd"  # cd-memo-init
    "cfec8db8ea83d5195094c735b64c68cf5a2a6d90c2e66d49cb18e75d99280963"  # README.md
    "b8c42f6ef4fa7552a40d029fa9e58eadf12090642febb21db1b47a13cca09f01"  # LICENSE
)

package() {
  install -Dm755 "$srcdir/cd-memo" "$pkgdir/usr/bin/cd-memo"
  install -Dm755 "$srcdir/cd-memo-init" "$pkgdir/usr/bin/cd-memo-init"
  install -Dm644 README.md "$pkgdir/usr/share/doc/$pkgname/README.md"
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}

