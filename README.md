# ロボットシステム学2018の課題1

## 課題内容内容
・デバイスドライバーの作成
・LEDの点灯、消灯

## 使い方
・コンパイル：make

・カーネルモジュールの追加：sudo insmod myled.ko
・権限の付与：sudo chmod 666 /dev/myled0
・LEDの点灯：echo 1 >/dev/myled0
・LEDの消灯：echo 0 >/dev/myled0
・後処理：sudo rm /dev/myled0
　　　　　sudo rmmod myled0

# ライセンス
