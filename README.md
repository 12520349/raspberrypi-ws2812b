# raspberrypi-ws2812b
#sudo nano /boot/config.txt
```
#dtoverlay=vc4-fkms-v3d
hdmi_force_hotplug=1
dtparam=i2c_arm=on
#dtparam=spi=on
enable_uart=1
dtoverlay=tft35a:rotate=180
dtoverlay=disable-audio
hdmi_group=2
hdmi_mode=1
hdmi_mode=87
hdmi_cvt 320 480 60 6 0 0 0
hdmi_drive=2
hdmi_force_edid_audio = 1
```

#Link
```
https://forums.raspberrypi.com/viewtopic.php?t=191210
```
