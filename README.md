## How to mount user data
grub2 menu.lst example:
```
title Android-x86 2019-05-04
    kernel /android-2019-05-04/kernel quiet root=/dev/ram0 SRC=/android-2019-05-04 USER_DATA=/dev/vdb1 USER_APP=com.tencent.mm
    initrd /android-2019-05-04/initrd.img
```
