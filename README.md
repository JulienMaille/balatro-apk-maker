# Balatro APK Maker

This goal of this script is to allow *Balatro* fans to play *Balatro* on their mobile devices before the official release. This script provides a **NON-PIRACY** avenue for players to do so, by converting their *Steam* version of *Balatro* to a mobile app. Balatro APK Maker also supports automatically transferring your saves from your *Steam* copy to your *Android* device.
While the name is Balatro "APK" Maker, iOS support exists-- But is experimental!
Keep in mind that Balatro APK Maker is still in beta! Please report any bugs you encouter in the [issues section](https://github.com/blake502/balatro-apk-maker/issues). If you encounter bugs with the latest release, try the previous release.

## Quick Start Guide
Please review the **Notes** section before you begin.
 - Download or compile [**balatro-apk-maker.exe**](https://github.com/blake502/balatro-apk-maker/releases).
 - Run **balatro-apk-maker.exe**.
 - Follow the prompts to apply optional patches. If you're unsure, always select "Y".
 ### For Android:
 - Copy the resulting **balatro.apk** to your Android device, or allow the program to automatically install using [USB Debugging](https://developer.android.com/studio/debug/dev-options).
 - Optionally, allow the program to automatically transfer your saves from your *Steam* copy of *Balatro* using [USB Debugging](https://developer.android.com/studio/debug/dev-options).
 ### For iOS:
 - Sideload **balatro.ipa** using [AltStore](https://altstore.io/)

 ## Optional Patches
- **FPS Cap**
Caps FPS to a desired number (Or to the device's native refresh rate-- recommended for battery performance)
- **Landscape Orientation**
Locks the game to landscape orientation (Recommended, since portrait orientation does not behave very well)
- **CRT Shader Disable**
Disables the CRT Shader (Recommended for Pixel and some other devices)

## Notes
 - This script assumes that **Balatro.exe** is located in the default *Steam* directory (`C:\Program Files (x86)\Steam\steamapps\common\Balatro\Balatro.exe`). If it is not, simply copy your **Balatro.exe** to the same folder as **balatro-apk-maker.exe**
 - This script will automatically download [7-Zip](https://www.7-zip.org/)
 ### For Android:
 - This script can automatically download and install [Java](https://www.java.com/en/download/)
 - This script will automatically download [APK Tool](https://apktool.org/)
 - This script will automatically download [uber-apk-signer](https://github.com/patrickfav/uber-apk-signer/)
 - This script will automatically download [love-11.5-android-embed.apk](https://github.com/love2d/love-android/)
 - This script will automatically download [Balatro-APK-Patch](https://github.com/blake502/balatro-apk-maker/releases/tag/Additional-Tools-1.0)
 ### For iOS:
 - This script can automatically download and install [Python](https://www.python.org/)
- This script will automatically download [Balatro-IPA-Base](https://github.com/blake502/balatro-apk-maker/releases/tag/Additional-Tools-1.0)

 ## Recogition (in no particular order)
 - [PGgamer2](https://github.com/PGgamer2) for many contributions (including language switching and dynamic FPS capping)
 - [TheCatRiX](https://github.com/TheCatRiX) for many contributions (including on-screen keyboard and save transferring)
 - [Sheep975](https://github.com/Sheep975) for kick-starting iOS support
 - [Blake502](https://github.com/Blake502) for initial release and continued support
 - Developers of [uber-apk-signer](https://github.com/patrickfav/uber-apk-signer)
 - Developers of [LÖVE](https://love2d.org/)
 - Developers of [7-Zip](https://www.7-zip.org/)
 - Developers of [APKTool](https://apktool.org/)
 - Delevopers of [Balatro](https://www.playbalatro.com/)

 ## License
 [7-Zip](https://github.com/ip7z/7zip/blob/main/DOC/License.txt) is licensed under the GNU LGPL license.
 
 This project uses [APKTool](https://github.com/iBotPeaches/Apktool/blob/master/LICENSE.md)
 
 This project uses [uber-apk-signer](https://github.com/patrickfav/uber-apk-signer/blob/main/LICENSE)
 
 This project uses [LÖVE](https://github.com/love2d/love/blob/main/license.txt)
