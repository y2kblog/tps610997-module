# TPS610997 超低消費電力 5V出力昇圧モジュール

<img src="/img/ProductImage_BothSide.jpg" width="350px">

## 概要

超低消費電力の5V出力昇圧型DC-DCコンバータ TPS610997 (Texas Instruments Inc.製) を搭載したモジュールです。  
TPS610997の**静止電流は約1μA程度**と非常に低く、また**0.7Vから動作**するため、コイン電池1個、もしくはアルカリ／ニカド／ニッケル水素乾電池1～2本で駆動するアプリケーションに適しています。  
さらに、TPS610997は**イネーブルピンによりシャットダウンが可能**であり、シャットダウン時は負荷が入力電源から切断されるため消費電流を低減できます。

### 仕様
- 入力電圧：0.7V～5.5V
- 出力電圧：5V (軽負荷時：5.15V)
- 最大出力電流：300mA（3.3V入力時）
  ※最大出力電流は入力電圧と効率に依存します
- 静止電流：1μA (軽負荷時)
- イネーブルピン付き
- 効率
  - 75% (入力電圧3.3V、負荷10μA)
  - 93% (入力電圧3.3V、負荷200mA)
- 基板サイズ：10mm × 6.35mm
- ピン間隔：2.54mm


## 販売  
[スイッチサイエンス委託販売ページ](https://www.switch-science.com/catalog/6505/)  
※大量注文や在庫に関する問い合わせは[こちら](mailto:info.y2kb@gmail.com)までご連絡ください。  


### 回路図  
<img src="/img/schematic.png" width="500px">


## 性能評価  

### 消費電流 (シャットダウン時 / 負荷100kΩ時 / 負荷1kΩ時)
<img src="/img/InputVoltage_LoadCurrent.png" width="500px">

## データシート  
[TPS61099xデータシート(日本語)](https://www.tij.co.jp/jp/lit/gpn/tps61099)

## License
MIT License
