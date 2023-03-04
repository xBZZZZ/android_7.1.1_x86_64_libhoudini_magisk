## libhoudini + magisk for android studio `Android 7.1.1 (Nougat)` `Intel x86 Atom_64 System Image`

`android_7.1.1_x86_64_libhoudini_magisk.7z.XXX` is split into multiple files to keep file sizes &le; 100MB

### files in this archive
| file name             | what?                                          |
| --------------------- | ---------------------------------------------- |
| README.md             | this text file                                 |
| system.img            | patched system.img with libhoudini             |
| ramdisk.img           | patched ramdisk.img with libhoudini and magisk |
| no_magisk_ramdisk.img | patched ramdisk.img with libhoudini            |
| Magisk-v25.2.apk      | magisk 25.2 apk (unmodified)                   |

### stuff included
- libhoudini 7.1.1a_y.49564 from https://github.com/Rprop/libhoudini/releases/tag/v7.1.1a_y.49564
- magisk 25.2 from https://github.com/topjohnwu/Magisk/releases/tag/v25.2

### prorams used to make this (not included)
- https://github.com/xBZZZZ/cpio_newc_dumper
- https://github.com/xBZZZZ/brimg
- bximage
- virtualbox (kde neon guest)
- https://7-zip.org/