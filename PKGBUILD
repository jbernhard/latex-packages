pkgname=texlive-jeb
pkgver=1.0
pkgrel=1
license=('MIT')
depends=('texlive-core')
pkgdesc="My custom latex packages."
url="https://github.com/jbernhard/latex-packages"
arch=('any')
install=texlive.install

source=(astro.sty avg.sty deriv.sty frac.sty quantum.sty short.sty unit.sty vector.sty)
sha512sums=('4b8e256e81af94c84b8b7b5e99dafc7b6ebff4b71d0e2cea149cc4c82921d07e1beda46bca546b9231b54f145d0675177c4e3d9aebe8902ce71aa22920233f89'
            '8861051537d178db7d02a8fc13da43ec347a0d29221184887d4e129cc52a176abb75fe34f48e14b3f33bc1774f2e8f89555d971e4de3988f2c02e54a12203f7b'
            '45fdcdcce064ed839ba503e69cbd9b71aca0ebb6a54a9688448adefda93ac6992da52a1cfb225740104f4827980005e651365e5c3c5fefde3403a6bcafab538e'
            '7fab2856efe8aa79ff2447b50f7153c2d44a295ab02284ed30a625e5901f93f76c00ebbba3fd002e9f2bb3be9263834f3f482bb87e2af249b321fb3abed36ead'
            '1b30933aaf7b05bfe906e3adca8775a484cfef01643d987e99de45a381fb0ccc7e4d9c57640709f8efe3b002f072e30b02eb173e91d2c7b2705f8ab8c96a6b88'
            'af542c24eb56c0094b1e7536a5c2e94200ed840bf51b6d690042aa563a224229a88764d2d03003aac3e49f353fbb20dedd744aea31de9b61210747de6b3ad5b6'
            '6cb41d1c331c379bf93edcc6733a28cbf2bd44b2a56b69ef6215bc918be7f20f7e7169deec1dc65dc3e55dabbe55ad477d5ac056bd7efc1193c7572aa0bcc27e'
            '3168e6cd690afb6cff1951658fbddf5ae30f3d8121067921dae59ca4f278c8497b9e88d2eafeb22fa0cca676c2d12384d9643b3a5c262b030a2f30c3edfb1f0e')

build() {
  mkdir -p $pkgdir/usr/share/texmf/tex/latex/jeb

  cp $srcdir/*.sty $pkgdir/usr/share/texmf/tex/latex/jeb
}
