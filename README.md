# RadioFieldAR

## Description

This software is for RTL-SDR.

You can see the radio field in AR(Augmented Reality).

This app is based on the software that introducing by following movie. 

But I modified some function for this release.

https://youtu.be/nCk2y98Kfto

![meas](https://user-images.githubusercontent.com/83148498/204128193-465ca9d4-eb96-4696-8462-3510307bcade.png)
![meas2](https://user-images.githubusercontent.com/83148498/204128203-c6b19222-81a9-4162-be59-7ded732d3277.png)

This software has lots of room of improvements.

But I hope to have this AR experience for many people first.

So I released this app as the alpha version.

Of cource the RF performance is depend on the RTL-SDR.

This is free software, please use it at your own risk.

## Required environment

![all](https://user-images.githubusercontent.com/83148498/204124730-910d67d5-dde6-4ce2-a6f2-db1c32f9a7e5.png)

### A smartphone that supports ARCORE.

You can check this web site.

https://developers.google.com/ar/devices

(FYI) I checked to work with the following devices.

SONY SOV38

SHARP AQUOS sense6

### RTL-SDR

https://www.rtl-sdr.com/
  
### OTG USB cable

There are many kinds of things. I have used this one.
  
https://www.amazon.co.jp/gp/product/B08LH1K2HF

### An antenna with printed picture for tracking

Plese use this one. The size should be around 50mm*50mm.

https://nomad-saving.com/wp-content/uploads/2016/03/NASA5-1-768x512.jpg

## How to install

#### 1. To install RTL-SDR driver
This app needs RTL-SDR driver.

So you can install the driver from google play.

https://play.google.com/store/apps/details?id=marto.rtl_tcp_andro

#### 2. Check to work properly RTL-SDR on your device.

I recommend to check working the RTL-SDR with your device before using this app.

This is the one of the app with RTL-SDR.

https://play.google.com/store/apps/details?id=com.mantz_it.rfanalyzer&hl=en&gl=US

#### 3.Install RadioFieldAR
I'm sorry this app can't be installed from the google play store.

You can install using APK file on the github.

Please refer to these web site for details.

https://www.lifewire.com/install-apk-on-android-4177185

JAPANESE

https://www.teradas.net/archives/6078/

## How to use
First, you start the app. And give permission for camera.

![camera](https://user-images.githubusercontent.com/83148498/204124012-45b7cf8f-7b43-4d71-851c-9e543337242a.png)

Then you will see the screen that driver starting.

![driver](https://user-images.githubusercontent.com/83148498/204124203-1a2f9386-4ad4-4996-ab41-611c94f1161e.png)

After that, the screen is like this.

![start](https://user-images.githubusercontent.com/83148498/204124237-abbfe6e8-de32-450e-9446-b3bfa4bccc41.png)

First, it is necessary to aim the camera slowly around the measurement object for the app recognize the surrounding environment.

[important]
ARCore requires visual information from the camera to build an environmental understanding. 
Rapid device movement can cause the camera image to become blurry, reducing ARCore's ability to track and detect features.
During brief periods of movement, ARCore relies on IMU data to estimate the device pose. When movement stops, visual tracking resumes.
Avoid extended periods of rapid movement, which can cause ARCore to lose tracking and prevent detection of features.

https://developers.google.com/ar/develop/runtime

![start_camera](https://user-images.githubusercontent.com/83148498/204124305-82d17741-a274-453f-8280-bf6740bc7563.png)

You can set frequency and gain. 
The size and grid value also can be changed.

![setting](https://user-images.githubusercontent.com/83148498/204124383-b47e04c9-7838-4e8f-ad4d-7126d164117c.png)

The play button is used for start and stop.
The cross mark is for clear the measurement result.

![start_camera2](https://user-images.githubusercontent.com/83148498/204124347-2654d4c4-808a-40e6-bc46-769b88ca7254.png)


Have a try! 
