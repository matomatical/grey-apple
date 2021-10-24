Grey Apple rEFInd theme
=======================

Based on (most icons and config):
[refind-dark-theme](https://github.com/samuelmeuli/refind-theme-dark)


![TODO: Screenshot taken by pressing F10 on rEFInd]()


Icons
-----

OS icons are 80px centered within 128px. SVG sources are included.
The grey is RGB(115,115,115), which might be a little lighter than
the apple?


Installation (macos)
--------------------

1. Mount EFI partition.
   ```
   sudo mkdir /Volumes/EFI
   sudo mount -t msdos /dev/disk0s1 /Volumes/EFI
   ```

2. Copy this repository into `/Volumes/EFI/EFI/refind/themes`.
    
3. Add the following line within `/Volumes/EFI/EFI/refind/refind.conf`:
   ```
   include themes/grey-apple/theme.conf
   ```


Roadmap
-------

* [x] Make icons grey
* [x] Make background
* [x] Make icons smaller, room for dot
* [x] Make selection dots
* [x] Restore some text and functions? Look at config info
* [ ] Hide double apple
* [ ] Install something other than macos
* [ ] Take screenshot and upload
* [ ] Linux instructions
* [ ] More icons?
* [ ] Clean up SVGs (get rid of inkscape bloat)


Links
-----

Other cool themes I spotted:

* Minimal
  * https://github.com/samuelmeuli/refind-theme-dark
  * https://github.com/CDLLY/rEFInd-minimal-dark
  * https://github.com/profojak/rEFInd-ThinkPad (but for mac)
* Cool:
  * https://github.com/Yannis4444/Matrix-rEFInd
  * https://github.com/enosich/refind-efifetch
  * https://github.com/AliciaTransmuted/rEFInd-chalkboard
* Pretty backgrounds or colours:
  * https://github.com/senpaiSubby/refind-sublime
  * https://github.com/ajlende/rEFInd-dawn
  * https://github.com/Wooniety/rEFInd-theme-Genshin-Impact
  * https://github.com/Chrisae9/rEFInd-mountain
  * https://github.com/josephsurin/refind-theme-circle

GitHub mirror of rEFInd source code (for reference)

* https://github.com/tianon/refind
