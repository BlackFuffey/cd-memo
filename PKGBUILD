# Maintainer: BlackFuffey ethanthecomputerman@gmail.com
pkgname=cd-memo
pkgver=oct2024v2
pkgrel=2
pkgdesc="Enhanced cd that memorizes your working directory across sessions"
arch=('any')
url="https://github.com/BlackFuffey/cd-memo"
license=('MIT')
depends=('bash')
source=("cd-memo" "cd-memo-init" "README.md" "LICENSE")
md5sum=(
    "7e42fad8fa975df5d620e5a1c3059329"    #cd-memo
    "4e838b12ee1be61046d3fdaf7620d79a"    #cd-memo-init
    "c0ea9286a02c4bc1b96e99078c0db87f"    #README.md
    "47378bd98a55d08b8846283fd4d11e11"    #LICENSE
)

package() {
    install -Dm755 "$srcdir/cd-memo" "$pkgdir/usr/bin/cd-memo"
    install -Dm755 "$srcdir/cd-memo-init" "$pkgdir/usr/bin/cd-memo-init"
    install -Dm644 README.md "$pkgdir/usr/share/doc/$pkgname/README.md"
    install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}

