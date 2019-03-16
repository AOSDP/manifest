<p align="center">
    <a href="#"><img src="https://raw.githubusercontent.com/AOSDP/AOSDP-assets/master/logo/PNG/logo-6.png"></a>
</p>

To initialize your local repository, use this command:

	repo init -u https://github.com/AOSDP/manifest.git -b 9.0
  
 Then to sync up:

```bash
repo sync -f --force-sync --no-tags --no-clone-bundle -j$(nproc --all)
```

Build AOSDP 
==================

```bash
source build/envsetup.sh
   
lunch aosdp_codename-buildtype
   
mka dark
```



__Our website: https://aosdp.com/__


__Our downloads website: https://downloads.aosdp.com/__
