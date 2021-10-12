# Summary

![](https://openailab.oss-cn-shenzhen.aliyuncs.com/logo/TengineKit.png?raw=true "TengineKit logo")

![](https://img.shields.io/crates/l/r)    

TengineKit, developed by OPEN AI LAB.       
TengineKit is an easy-to-integrate AI algorithm SDK. At present, it can run on various mobile phones at very low latency.**We will continue to update this project for better results and better performance!**

## Have a try
- [Apk](Android/apk/TengineKitDemo-v1.0.3.apk) can be directly downloaded and installed on the phone to see the effect.
or
- scan code to download apk 

![Apk](https://www.pgyer.com/app/qrcode/A0uD?sign=&auSign=&code=)

## Goals
- Provide best performance in mobile client
- Provide the simplest API in mobile client
- Provide the smallest package  in mobile client

## Features
- face detection
- face landmarks
- face 3dlandmarks
- face attributes for example: age, gender, smile, glasses
- eye iris & landmarks
- body detect
- hand detect(Real-time, not yet on Mobile)
- hand landmarks(Real-time, not yet on Mobile)
- body detect google(Real-time, not yet on Mobile)
- body landamrks(Real-time, not yet on Mobile)
- yolov5

## Update (2021/03/25)
- Fixed Linux sample code errer
- Update Android sample code, up fps
- update Linux so file
- update Linux yolov5s
- Fixed memory(Core v0.0.6)

## Performance(Face Detect & Face Landmark)

| CPU | Time consuming | Frame rate |
| :---: | :---: | :---: |
| Kirin 980 | 4ms | 250fps | 
| Qualcomm 855 | 5ms | 200fps |
| Kirin 970 | 7ms | 142fps |
| Qualcomm 835 | 8ms | 125fps |
| Kirin 710F| 9ms | 111fps |
| Qualcomm 439 | 16ms | 62fps |
| MediaTek Helio P60 | 17ms | 59fps |
| Qualcomm 450B | 18ms | 56fps |


