# TWRP device tree for Vsmart V420A (Vsmart Joy 2+)

## About Device

![Vsmart V420A](https://cdn.tgdd.vn/Products/Images/42/209555/vsmart-joy-2-plus-2gb-green-400x460.png)

### Specifications


Component Type | Details
--------------:|:-------
Brand | Vsmart
Model | Joy 2+
Release date | Aug 2019
Launched in Vietnam | Yes
Form factor | Touchscreen
Body type | Plastic
Dimensions (mm) | 156.70 x 75.30 x 8.30
Weight (g) | 155.00
Battery capacity (mAh) | 4500
Removable battery | No
Wireless charging | No
Display | -
Screen size (inches) | 6.20
Touchscreen | Yes
Resolution | 720x1520 pixels
Aspect ratio | 19:9
Hardware | -
Processor Clock Speed | 1.8GHz octa-core
Processor Model | Qualcomm Snapdragon 450
RAM | 2/3GB
Internal storage | 16/32GB
Expandable storage | Yes
Expandable storage type | microSD
Expandable storage up to (GB) | 256
Dedicated microSD slot | Yes
Camera | -
Rear camera | 13-megapixel (f/2.0) + 5-megapixel (f/2.4)
Rear autofocus | Phase detection autofocus
Rear flash | Yes
Front camera | 8-megapixel (f/2.2)
Software | -
Operating system | Android 9.0
Skin / UI | VOS 2.0/2.5
Connectivity | -
Wi-Fi | Yes
Bluetooth | Yes
Sensors | -
Face unlock | Yes
Compass/ Magnetometer | Yes
Proximity sensor | Yes
Accelerometer | Yes
Ambient light sensor | Yes

**This device tree can be used to build twrp for Vsmart V420A (Vsmart Joy2+)**

## Build Instructions
```sh
source build/envsetup.sh
lunch omni_V420A-eng
or
lunch omni_V420A-userdebug
mka recoveryimage
```
