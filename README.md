Grey Apple rEFInd theme (WIP)
=============================


![Press F10 to save screenshots to ESP root](screenshots/animation.gif)


Based on (most icons and config):
[refind-dark-theme](https://github.com/samuelmeuli/refind-theme-dark)

Roadmap:

* [x] Make icons grey
* [x] Make background
* [x] Make icons smaller, room for dot
* [x] Make selection dots
* [x] Restore some text and functions? Look at config info
* [x] Preliminary screenshot
* [x] Make the function icons smaller (and remove some)
* [x] Hide double apple
* [x] Install something other than macos
* [x] Screenshot with linux
* [x] Animated screenshot like [this genius](https://github.com/Chrisae9/rEFInd-mountain)
* [ ] Add linux install/config instructions to README
* [ ] Clean up SVGs (get rid of inkscape bloat)
* [ ] More icons?



Icons
-----

OS icons are 80px centered within 128px. SVG sources are included.
The grey is RGB(115,115,115), which might be a little lighter than
the apple?


Installation (macos)
--------------------

1. Mount EFI partition.
   ```
   sudo mkdir /Volumes/ESP
   sudo mount -t msdos /dev/disk0s1 /Volumes/ESP
   ```

2. Clone this repository into `/Volumes/ESP/EFI/refind/themes`.
    
3. Add the following line within `/Volumes/ESP/EFI/refind/refind.conf`:
   ```
   include themes/grey-apple/theme.conf
   ```

Links
-----

rEFInd website, documentation, source code

* https://rodsbooks.com/refind/index.html
* github mirror (for reference)
  https://github.com/tianon/refind

Other cool themes I spotted:

* Minimal:
  * https://github.com/samuelmeuli/refind-theme-dark
  * https://github.com/CDLLY/rEFInd-minimal-dark
  * https://github.com/profojak/rEFInd-ThinkPad
    (I'm trying to do this, but for mac)
* Super cool:
  * https://github.com/Yannis4444/Matrix-rEFInd
  * https://github.com/enosich/refind-efifetch
  * https://github.com/AliciaTransmuted/rEFInd-chalkboard
* Pretty backgrounds or colours:
  * https://github.com/senpaiSubby/refind-sublime
  * https://github.com/ajlende/rEFInd-dawn
  * https://github.com/Wooniety/rEFInd-theme-Genshin-Impact
  * https://github.com/Chrisae9/rEFInd-mountain
  * https://github.com/josephsurin/refind-theme-circle
* The rEFInd website also has a list of themes.