# Maintainer: BlackFuffey ethanthecomputerman@gmail.com
pkgname=cd-memo
pkgver=2024.11.v1
pkgrel=3
pkgdesc="Enhanced cd that memorizes your working directory across sessions"
arch=('any')
url="https://github.com/BlackFuffey/cd-memo"
license=('MIT')
depends=('bash')
source=("cd-memo" "cd-memo-init" "README.md" "LICENSE")

package() {
    install -Dm755 "$srcdir/cd-memo" "$pkgdir/usr/bin/cd-memo"
    install -Dm755 "$srcdir/cd-memo-init" "$pkgdir/usr/bin/cd-memo-init"
    install -Dm644 README.md "$pkgdir/usr/share/doc/$pkgname/README.md"
    install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}

sha256sums=('1f5bb155cab9f6548d8c5bb0975427fa9ee0d310fe245a27c75c7d18144d5f9a'
            'f7f86e8cb9960cc740e99d286a434612a4d44faccc62ea96f92aa97e02d46008'
            '59355db27186175739db9acd05a49f52b60aa5d04039eb14abd73eded6471ab2'
            'b8c42f6ef4fa7552a40d029fa9e58eadf12090642febb21db1b47a13cca09f01')
