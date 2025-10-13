source: [AlteriaX/WuWa-Configs-Android](https://github.com/AlteriaX/WuWa-Configs-Android)

Config location for Android \
```Android/data/com.kurogame.wutheringwaves.global/files/UE4Game/Client/Client/Saved/Config/Android```

Use Shizuku if you can't access the folder \
[Shizuku](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api&hl=en)

Recommended file manager \
[ZArchiver](https://play.google.com/store/apps/details?id=ru.zdevs.zarchiver&hl=en)

---

source: [Shxvi/wuwa-configs](https://github.com/Shxvi/wuwa-configs)

# Config doesn't work!
1. Open `DevicesProfiles.ini` with text editor of your choice
2. Add your device Model/GPU, if not sure add both:\
Find your device specifications at [GSMArena](https://www.gsmarena.com)\
Write your specs as in example for Poco X6 Pro bellow:
```
[Android_VeryHigh DeviceProfile]                                                ↰
some parameters                                                                 |
some more parametrs                                                             |
and maybe even more                                                             |
                                                                                |
[2311DRK48G DeviceProfile]                   <----- Model of Poco X6 Pro        |
BaseProfileName=Android_VeryHigh             <----- Name of graphics profile    ↲

[Android_Mali_G615-MC6 DeviceProfile]        <----- Dimensity 8300's GPU name, SoC from Poco X6 Pro
BaseProfileName=Android_VeryHigh

[Android_Mali_G615 DeviceProfile]            <----- Another possible name of D8300's GPU
BaseProfileName=Android_VeryHigh
```
