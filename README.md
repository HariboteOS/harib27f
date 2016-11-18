# harib27f
「30日でできる！OS自作入門」の最終日バージョンをもとに、マルチプラットフォーム対応等を加えたものです。

OSのソースコード自体は、本のCDに付属しているharib27fと全く等価になっています。

## 追加された機能
- マルチプラットフォームでの開発に対応
 - 各環境に合わせて、修正版のz_toolsをダウンロードして差し替えるだけで、ソースを修正することなくコンパイル・実行が可能です。
  - [Mac OSX版](https://github.com/HariboteOS/z_tools_osx)
  - [ソースコード](https://github.com/HariboteOS/tolsrc)

- bochs対応
 - `make brun`で実行できます。

## ライセンス
KL-01
