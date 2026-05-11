# Android One Experience #

### Source'u indirme ###

```bash

repo init --depth=1 -u https://github.com/GM-AndroidOne-Archive/androidone_manifest -b ten

repo sync
```

### Derleme ###

```bash

$ . build/envsetup.sh

$ lunch aosp_$device-userdebug

$ mka bacon -jX
```
### Neler vaat ediyor? ###

En dogal Android One deneyimini yasayabilmeniz icin tasarlandi. PixelExperience tabanlidir, custom detaylardan arindirilmis ve GM cihazlar icin optimize edilmistir. En iyi sonuc icin GM-AndroidOne-Archive organizasyonundaki kaynaklari kullanmaniz onerilir.

Yigit Emre Yanik (yigityanik)