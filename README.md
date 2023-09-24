### wallx
Thanks to AyraHikari for this app https://github.com/AyraHikari/WallYouX/releases

clone 
```bash
   git clone https://github.com/Alioth-Tree/vendor_wallx.git vendor/wallx
```

To build with wallxAyra add this line in device.mk or (rom)_(device).mk
```bash
   # wallxAyra
   $(call inherit-product-if-exists, vendor/wallx/wallxayra.mk)
```

