# harib27f
「30日でできる！OS自作入門」の最終日バージョンをもとに、マルチプラットフォーム対応等を加えたものです。

OSのソースコード自体は、本のCDに付属しているharib27fと全く等価になっています。

## つかいかた
### ディレクトリの配置
- まず、以下のようなディレクトリ構成になるよう、各リポジトリをクローンしてください。
  - `harib27f`と`z_tools`が同一の階層に存在するようにしてください。
```
haribote_os/
    harib27f/
        ...
    z_tools/
        ...
```
- ここで、`z_tools`は、[z_tools_win](https://github.com/HariboteOS/z_tools_win), [z_tools_osx](https://github.com/HariboteOS/z_tools_osx), [z_tools_linux](https://github.com/HariboteOS/z_tools_linux)のいずれかを`z_tools`にリネームしたものです。お使いの環境に合わせて選択してください。

### コンパイル・実行
- 配置できたら、`harib27f`ディレクトリに移動してから、`make full`コマンドを実行し、コンパイルしてください。
- エラーなく終了すれば、`make run`, `make brun`などの各種コマンドで実行できます。

## 追加された機能
- マルチプラットフォームでの開発に対応
 - 各環境に合わせて、修正版のz_toolsをダウンロードして差し替えるだけで、ソースを修正することなくコンパイル・実行が可能です。
  - [Mac OSX版](https://github.com/HariboteOS/z_tools_osx)
  - [ソースコード](https://github.com/HariboteOS/tolsrc)

- bochs対応
 - `make brun`で実行できます。

## ライセンス
KL-01
