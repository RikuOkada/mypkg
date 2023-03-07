![test](https://github.com/RikuOkada/sisutemugaku/actions/workflows/test.yml/badge.svg)

ROS2パッケージです。

# 説明

* talker - listener 間でトピック通信を行います。

* talker.py

  0.5秒ごとに1増加する数値を送信するノード

* listener.py

  talkerで送信されたメッセージを受け取って端末に表示するノード

* talk_listen.launch.py

  talkerとlistenerを同時に立ち上げるためのlaunchファイル。

# テスト環境
* ROS2 Humble

* Ubuntu 22.04

* Python 3.10.6


# ライセンス
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
* このパッケージのコードは、下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを、本人の許可を得て自身の著作としたものです。
* [ryuichiueda/my_slides_robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022) ©  2022 Ryuichi Ueda
* ©　2023　Riku Okada
