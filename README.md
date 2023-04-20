### wallxAyra
Thanks to AyraHikari for this app https://github.com/AyraHikari/WallYouX/releases

clone 
```bash
   git clone https://github.com/Ghosuto/vendor_wallxAyra.git vendor/wallxAyra
```

To build with wallxAyra add this line in device.mk or (rom)_(device).mk
```bash
   # wallxAyra
   $(call inherit-product-if-exists, vendor/wallxAyra/wallxAyra.mk)
```

