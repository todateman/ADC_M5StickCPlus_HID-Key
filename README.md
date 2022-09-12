# ADC_M5StickCPlus_HID-Key
M5StickC用のADC Hatを用いて、アナログ電圧を取り込んでBluetooth hidでBluetooth HIDキーボードでPC/タブレットに送信可能な機能を持たせました。

Using ADC Hat for M5StickC, we have added the ability to take analog voltage and send it to a PC/tablet with a Bluetooth HID keyboard via Bluetooth hid.

# 説明 explanation
[ADC Hat](https://docs.m5stack.com/en/hat/hat-adc)で0～12Vの直流電圧を取り込み、[ESP32-BLE-Keyboard](https://github.com/T-vK/ESP32-BLE-Keyboard)でBluetooth HIDキーボードとしてPC/タブレットに送信します。
手元にDC出力可能なわかりやすいセンサーが無かったので、[M5Stack FacesのEncoderパネル](https://docs.m5stack.com/en/module/encoder)を用いて0～3.3Vの範囲で再現しています。


※実際に業務では[キーエンス・IL](https://www.keyence.co.jp/products/sensor/positioning/il/)のアナログ電圧出力をADC Hat経由でM5StickC Plusに取り込んで、Bluetooth HIDキーボードでPC/タブレットに送信し電子帳票に入力して運用しているのですが、業務での成果物をそのまま公表することはできないのでプライベートの機材で投稿します。


Capture 0-12V DC voltage with [ADC Hat](https://docs.m5stack.com/en/hat/hat-adc) and send it to a PC/tablet as a Bluetooth HID keyboard with [ESP32-BLE-Keyboard](https://github.com/T-vK/ESP32-BLE-Keyboard ) to a PC/tablet as a Bluetooth HID keyboard.
Since we did not have an obvious sensor with DC output capability at hand, we used [Encoder panel of M5Stack Faces](https://docs.m5stack.com/en/module/encoder) to reproduce a range of 0 to 3.3V.


*In actual work, the analog voltage output from [Keyence, IL](https://www.keyence.com/products/sensor/laser/il/) is taken into the M5StickC Plus via ADC Hat and Bluetooth HID keyboard to a PC/tablet and input into electronic forms for operation. However, I cannot publish the work product as it is at work, so I am posting it with my private equipment.

Translated with www.DeepL.com/Translator (free version)


[M5Stack Japan Creativity Contest 2022 参加作品](https://protopedia.net/event/m5stack2022)

[Works that participated in "M5Stack Japan Creativity Contest 2022"](https://protopedia.net/event/m5stack2022)
