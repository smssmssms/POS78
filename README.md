# pos78

![KB-78](https://raw.githubusercontent.com/smssmssms/POS78/main/KB-78.png)

* Keyboard Maintainer: [smssmssms](https://github.com/smssmssms)
* Hardware Supported: ATMEGA 32U4 (Adafruit Itsy Bitsy 5v to replace the original controller)
* Hardware Availability: 1980-90's Partner Tech Corp KB-78; a 78 key Point-Of-Sale ortholinear keyboard conversion
  https://www.partner.com.tw/wp-content/uploads/2019/09/KB-78-G-78-1-190911.pdf

Example on how to compile and flash the keyboard (after setting up the build environment (https://docs.qmk.fm/#/getting_started_build_tools))
    
    qmk flash -kb pos78 -km default

Only want to compile the firmware?
    
    qmk compile -kb pos78 -km default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. 

Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
