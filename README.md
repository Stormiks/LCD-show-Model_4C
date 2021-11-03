# 4inch RPi LCD (C) for Raspberry Pi 4B

### Description:

This is a 4inch TFT LCD with resistive touch panel, has 480x320 resolution. Support up to 125MHz high-speed SPI signal transmission provide you a clear and stable display effect. Can directly plug to any revision of Raspberry Pi. Driver is provided for Raspbian.

P.S.: Tested on the latest full Raspberry OS build.

---

### Website:

EN: https://www.waveshare.com/4inch-rpi-lcd-c.htm

### WiKi:

EN: https://www.waveshare.com/wiki/4inch_RPi_LCD_(C)

### Driver install:

```bash
chmod +x LCD4C-show
sudo ./LCD4C-show
```

### Screen orientation settings

After touch driver is installed, the screen orientation can be set by these commands:

- 90 degree rotate
```bash
cd LCD-show/
./LCD4C-show 90
```
- 180 degree rotate
```bash
cd LCD-show/
./LCD4C-show 180
```
- 270 degree rotate
```bash
cd LCD-show/
./LCD4C-show 270
```

---

P.S: Original repository: 
```bash
git clone https://github.com/waveshare/LCD-show.git
```