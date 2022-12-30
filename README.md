# color_msgs
このリポジトリはROS2のパッケージです。srcディレクトリでgit cloneすればパッケージとして利用できます。

## 依存関係
このパッケージは[mypkgパッケージ](https://github.com/ogi-y/color_msgs)を利用するために必要です。

## Color型の説明
* Color型は以下のように定義されています。
    * string color_code
    * uint64 red
    * uint64 green
    * uint64 blue

## サービスの説明
* サービスを呼び出す方が渡すデータは以下の３つです。
    * uint64 red
    * uint64 green
    * uint64 blue
* サービス実行後に呼び出した方が受け取るデータは以下です。
    * string color_code

## 必要なソフトウェア
* Python 3.7～3.10

## テスト環境
* Ubuntu 22.04.1 LTS

## 権利表記
* このソフトウェアパッケージは、[3条項BSDライセンス](https://opensource.org/licenses/BSD-3-Clause)の下、再頒布および使用が許可されます。
* © 2022 Yoshihiro Ogishima