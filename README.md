# Retroid Pocket 3 OCD Setup (work-in-progress)

The rules for this setup are:
* no Google Play
* minimal APKs from non-official sources
* only the 38 systems shown in the Emulation section of the Retroid launcher
* only one stand-alone (non-Retroarch) emulator per system

Steps:
* factory reset
* setup wizard: install redream, Mupen64Plus FZ, Gamepad Tester / select AOSP launcher
* settings > display: brightness 50%, timeout 2 minutes, largest font
* format SD card, set up as portable storage, clear notification
* run and exit redream and Mupen64Plus FZ
* install, run and exit: (as of 2022-09-15)
  * Moonlight [10.8.1 APK](https://github.com/moonlight-stream/moonlight-android/releases/download/v10.8.1/app-root-release.apk) / [source](https://github.com/moonlight-stream/moonlight-android/releases)
  * RetroArch [1.10.3 APK](https://buildbot.libretro.com/stable/1.10.3/android/RetroArch_aarch64.apk) / [source](https://www.retroarch.com/?page=platforms)
  * PSP - PPSSPP [1.13.2 APK](https://ppsspp.org/files/1_13_2/ppsspp.apk) / [source](https://ppsspp.org/downloads.html) - set Memory Stick to internal storage for now
  * PS1 - Duckstation [0.1-4568 APK](https://www.duckstation.org/android/duckstation-android.apk) / [source](https://www.duckstation.org/android/)
  * PS2 - AetherSX2 [1.2-2637 APK](https://www.aethersx2.com/archive/monthly/12899-v1.2-2637.apk) / [source](https://www.aethersx2.com/archive/)
  * Saturn - Yaba Sanshiro 2 [2.1.5 APK](https://uoyabause.org//apks/YabaSanshiro-V58-2.1.5-180821-release.apk) / [source](https://uoyabause.org/static_pages/download) - silence its notifications
  * 3DO - Real3DOPlayer [1.0.32 APK](https://archive.org/download/ru.vastness.altmer.real3doplayer-1.0.32/ru.vastness.altmer.real3doplayer-1.0.32-full.apk) / [source](https://archive.org/details/ru.vastness.altmer.real3doplayer-1.0.32)
  * 3DS - Citra MMJ [20220913 APK](https://github.com/weihuoya/citra/releases/download/20220913/Citra_MMJ_20220913.apk) / [source](https://github.com/weihuoya/citra/releases)
  * Gamecube/Wii - Dolphin MMRJ [1.0-11505 APK](https://github.com/Bankaimaster999/Dolphin-MMJR/releases/download/1.0-11505/app-release.apk) / [source](https://github.com/Bankaimaster999/Dolphin-MMJR/releases/tag/1.0-11505)
  * DS - use RetroArch
* [download icon for Retroid Launcher](https://raw.githubusercontent.com/r0b0-tr0n/rp3ocd/main/grunt.webp) - need different link
* run Retroid Launcher, dark mode, set icon, set name, turn on show background
* change time to 12-hr
* go to Emulation, turn on all systems
* Setup > Create ROM Folders > SD Card
* Setup > RetroArch setup > OK
* Setup > Standalone setup > Do each one
* 
