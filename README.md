# ロボットシステム学2018の課題1

## 課題内容
・デバイスドライバーを作成し、何かを行う。

## 説明

### 内容
講義内容（https://github.com/ryuichiueda/robosys2018）に沿ってデバイスドライバーを作成し、LEDの点灯、消灯を行った。

### 使い方
・コンパイル：make

・カーネルモジュールの追加：sudo insmod myled.ko

・権限の付与：sudo chmod 666 /dev/myled0

・LEDの点灯：echo 1 >/dev/myled0

・LEDの消灯：echo 0 >/dev/myled0

・後処理：sudo rm /dev/myled0
　　　　sudo rmmod myled0

# ライセンス
