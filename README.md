this archive is from https://github.com/xBZZZZ/android_7.1.1_x86_64_libhoudini_magisk

`android_7.1.1_x86_64_libhoudini_magisk.7z.XXX` is split into multiple files to keep file sizes < 100MB

## libhoudini + magisk for android studio `Android 7.1.1 ("Nougat")` `Intel x86_64 Atom System Image`

### files in this archive
| file name             | what?                                                             |
| --------------------- | ----------------------------------------------------------------- |
| README.md             | this text file                                                    |
| system.img            | patched system.img with libhoudini and hardlinked duplicate files |
| ramdisk.img           | patched ramdisk.img with libhoudini and magisk                    |
| no_magisk_ramdisk.img | patched ramdisk.img with libhoudini                               |
| Magisk-v27.0.apk      | magisk 27.0 apk (unmodified)                                      |

### stuff included
- libhoudini from https://archive.org/download/androidx86-houdini/Houdini%20%5BNougat%5D%20%5B7.1%5D/houdini64.zip
  - `/system/lib64/arm64/houdini64 --version`: `Houdini version: 7.1.0a_z.49344`
  - `/system/lib/arm/houdini --version`: `Houdini version: 7.1.0a_y.49344`
- magisk 27.0 from https://github.com/topjohnwu/Magisk/releases/tag/v27.0

### prorams used to make this (not included)
- https://github.com/xBZZZZ/cpio_newc_dumper
- https://github.com/xBZZZZ/brimg
- bximage from https://sourceforge.net/projects/bochs/files/bochs/2.7/bochs-2.7-1.src.rpm/download
- virtualbox 7.0.14 (linux mint 21.3 cinnamon guest)
- https://7-zip.org/download.html (24.00 beta 7-Zip for Linux: console version)
- https://github.com/xBZZZZ/gzsimp
- https://f-droid.org/packages/com.ghostsq.commander/
- https://github.com/fhanau/Efficient-Compression-Tool
- https://encode.su/threads/1214-defluff-a-deflate-huffman-optimizer

for libhoudini 7.1.1a_y.49564 that supports only armeabi-v7a and armeabi see https://github.com/xBZZZZ/android_7.1.1_x86_64_libhoudini_magisk/tree/only32bit