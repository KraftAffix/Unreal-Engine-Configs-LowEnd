source: [AlteriaX/WuWa-Configs-Android](https://github.com/AlteriaX/WuWa-Configs-Android)

Config location for Android \
```Android/data/com.kurogame.wutheringwaves.global/files/UE4Game/Client/Client/Saved/Config/Android```

Use Shizuku if you can't access the folder \
[Shizuku](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api&hl=en)

Recommended file manager \
[ZArchiver](https://play.google.com/store/apps/details?id=ru.zdevs.zarchiver&hl=en)

---

# Config doesn't work
1. Open `DevicesProfiles.ini` with text editor of your choice
2. Add your device GPU\
Find your device specifications at [GSMArena](https://www.gsmarena.com) or use [Device Info HW](https://play.google.com/store/apps/details?id=ru.andr7e.deviceinfohw) App on Googple Play\
Write your specs as in example for Infinix HOT 60 Pro below:
```
[Android_Low DeviceProfile]                                                   ↰
CVars=r.MobileContentScaleFactor=1.5                                           |
CVars=r.SecondaryScreenPercentage.GameViewport=50                              |
CVars=r.imp.SSMbScaleLod0=3.0                                                  |
CVars=r.imp.SSMbScaleLod1=3.0                                                  |
CVars=r.Mobile.DeviceEvaluation=3                                              |
                                                                               |
[Android_Mali_G57-MC2 DeviceProfile]      <--- Name of GPU                     |
BaseProfileName=Android_Low               <--- Name of graphics profile       ↲

[Android_Mali_G57 DeviceProfile]          <--- Other possible name of Mali G57's GPU
BaseProfileName=Android_Low
```
