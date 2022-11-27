# Sorry currently under construction 

# RadioFieldAR
RadioFieldAR


## Description

This software is for RTL-SDR.

You can see the radio field in AR(Augmented Reality).

!!!!There is a video introducing this app on youtube.

!!!![https://youtu.be/LzDLyCjDgJU](https://youtu.be/nCk2y98Kfto)

This software has lots of room of improvements.

But first, I hope to have this AR experience for many people.

I released this app as alpha version.

Also RF performance is depend on the RTL-SDR.

This is free software, please use it at your own risk.

## Required environment
### A smartphone that supports ARCORE.

You can check this web site.

https://developers.google.com/ar/devices

(FYI) I checked to work on the following devices.

SONY SOV38

SHARP AQUOS sense4

SHARP AQUOS sense6

### RTL-SDR

https://www.rtl-sdr.com/
  
### OTG USB cable

There are many kinds of things. I have used this one.
  
#### https://www.amazon.co.jp/gp/product/B08LH1K2HF

### An antenna with printed picture for tracking

Plese use this one. The size should be 50mm*50mm.
https://nomad-saving.com/wp-content/uploads/2016/03/NASA5-1-768x512.jpg

You can use the PC or smartphone's screen instead.
But tracking performance may be decreased.

## How to install

#### 2. To install RTL-SDR driver
This app needs RTL-SDR driver.

So you can install the driver from google play.
https://play.google.com/store/apps/details?id=marto.rtl_tcp_andro

#### 3. Check to work properly RTL-SDR on your device.

I recommend to check working the RTL-SDR with your device before using this app.

This is the one of the app with RTL-SDR.

https://play.google.com/store/apps/details?id=com.mantz_it.rfanalyzer&hl=en&gl=US

#### 4.Install RadioFieldAR
I'm sorry this app can't be installed from the google play store.

You can install using APK file on the github.

Please refer to these web site for details.

https://www.lifewire.com/install-apk-on-android-4177185

JAPANESE

https://www.teradas.net/archives/6078/

## How to use
まずアプリを立ち上げるとカメラの許可が表示されるので許可してください。

![camera](https://user-images.githubusercontent.com/83148498/204124012-45b7cf8f-7b43-4d71-851c-9e543337242a.png)

ドライバ動作の画面が表示されます。

![driver](https://user-images.githubusercontent.com/83148498/204124203-1a2f9386-4ad4-4996-ab41-611c94f1161e.png)

その後スペクトルとカメラ画面になります。

![start](https://user-images.githubusercontent.com/83148498/204124237-abbfe6e8-de32-450e-9446-b3bfa4bccc41.png)

始めに測定する部分の空間を認識させるため、スマートフォンをゆっくり動かしながら
周りの空間を撮影してください。これをすることで、空間に座標が作成されます。
次にカメラで認識用イメージを撮影してください。認識されると星がイメージの中心に表示され
スマートフォンやイメージを動かしても追従するのが確認できます。
急激に動かすと追従が追い付かないのでゆっくり動かしてください。
![start_camera](https://user-images.githubusercontent.com/83148498/204124305-82d17741-a274-453f-8280-bf6740bc7563.png)

次に測定対象の周波数を設定します。受信レベルに応じてゲインは調整してください。
サイズとグリッドは測定エリアに応じて調整してください。
![setting](https://user-images.githubusercontent.com/83148498/204124383-b47e04c9-7838-4e8f-ad4d-7126d164117c.png)


狭いところを見る場合は小さく、広いところを見るには大きくします。
スタートボタンを押すと認識されているイメージの場所にFOGを描画していきます。
×ボタンを押すとクリアされます。
![start_camera2](https://user-images.githubusercontent.com/83148498/204124347-2654d4c4-808a-40e6-bc46-769b88ca7254.png)






