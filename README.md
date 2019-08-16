4.4 kernel for OnePlus 3/3T
==========

Right now it boots to LineageOS 16.0

## What works

* Display
* Sound
* Camera
* Touchscreen (but keypad fw update leads to a kernel panic)
* NFC
* WiFi/BT/RIL
* Vibrator
* Sensors

## What doesn't work

* USB
* The entire power stack (including battery and dash charger)
* Other random unnoticed stuff

## Future work

* Rewrite part of the power stack to fix it. The power supply framework was refactored a lot from 3.18 to 4.4. MSM8996 uses QPNP SMB Charger while MSM8998 uses SMB2 Battery Charger so we can't kang from OP5/5T despite they're from the same OEM.
* This is my hobby project and I develop it in my spare time. I'm busy with real-life work and study thus I don't set a ddl for it and it's possible that the port is never finished.

## Contribute

* Contributions to are welcomed and appreciated. Feel free to send a pull request containing **bug fixes** towards the port. Warning fixes, security patches, features and other rices will be **ignored**.
* [Donate](https://www.paypal.me/dianlujitao) on PayPal to support my work.