## Mac

```
$ esptool.py --port /dev/cu.SLAB_USBtoUART write_flash -fm=dio -fs=32m 0x00000 bin/0x00000.bin 0x10000 bin/0x10000.bin
```
