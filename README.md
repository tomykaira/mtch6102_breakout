# mtch6102_breakout
Breakout board of MTCH6102, a 2D capacitive touch sensor, for DIY split keyboards with TRRS connectors.

静電容量式タッチセンサIC MTCH6102のブレークアウトボードです。
2個のTRRSコネクタを取り付けることで、自作スプリットキーボードの間に挟んで動作させることができます。(キーボードがI2Cでの通信に対応している必要があります)

## はんだ付けの注意

表面実装部品は左側の列から付けることをお勧めします。ただし、C1, C3はそれぞれU1, U2の後に付けたほうがよいです。

D1, D2, D3, U2をつける際は向きに注意してください。
![半田面](https://github.com/sekigon-gonnoc/mtch6102_breakout/blob/master/bottom.JPG "はんだ面")

|シルク|個数|パッケージ|部品|
|--|--|--|--|
|Q1|1|SOT-23|Pch FET|
|Q2|1|SOT-363|Nch FET|
|R1|1|1608抵抗|10kΩ|
|R2, R3, R4, R5|4|1608抵抗|2.2kΩ|
|C1, C2|2|1608コンデンサ|1μF|
|C3|1|1608コンデンサ|0.1μF|
|D1|1|SOT-323|ショットキーバリアダイオード|
|D2, D3|2|SOT-323|ダイオード|
|U1|1|SOT23-5|三端子レギュレータ|
|U2|1|SSOP28|MTCH6102|
