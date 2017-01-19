Zephyr Utils
############

Image signing
=============

Image signing is required when booting Zephyr applications via the MCU boot
loader (https://github.com/runtimeinc/mcuboot).

To sign a zephyr image:

```
$ python zep2newt.py --bin $ZEPHYR_APP_PATH/outdir/$BOARD/zephyr.bin --key root.pem --sig RSA --out app.signed.bin
```
