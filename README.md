## Recovery Device Tree for the Samsung Galaxy S22 5G (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_r0s-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_exynos2200
