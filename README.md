# Melina Kernel (for LG G6 US997 Variant)

**Note**: This is for the US997, **NOT** the US997U (aka LG G6+)

Based on LGE Opensource v10b kernel (first commit)

## Information

 * For use on LG Nougat Stock ROMs
 * Tested on LGE Stock US997v16a
 
## Features:

 * Binary releases built with ubertc aarch64-linux-android-6.x
 * DriveDroid CD-ROM Emulation Support
 * Open source compatible replacement for Tuxera exFAT driver
 * Various other improvements

## Current Status:

 * Compiles: Yes
 * Boots: Yes
 * Bugs: None known

## How to build:

 * Edit .zefie/scripts/buildenv.sh, and set TOOLCHAIN for your local setup
 * Run .zefie/scripts/fullbuild.sh

If all goes well, output will be in build/out/,
and you can also use .zefie/scripts/sideload.sh to automatically sideload the most recent zip to TWRP.

## Credits

 Commits have been cherry-picked from the following sources:

 * [CrazyAquaKernel for LineageOS by CrazyGamerGR](https://github.com/CrazyGamerGR/CrazyAquaKernel-g5-g6-los-nougat)
 * [DX-Mi5 by pappschlumpf](https://github.com/pappschlumpf/DX-Mi5)
 * [Noire Kernel by me](https://git.zefie.net/zefie/android_kernel_samsung_msm8916)


## Benchmarks

Stock Kernel (16a) | Melina Kernel ([ga4e29e9](https://git.zefie.net/zefie/lge_us997_melina_kernel/commit/a4e29e906665a3062bd4d6a0d6fffcb912f403cd))
--- | ---
![Image](.zefie/benchmarks/stock_lge_16a_kernel.jpg?raw=true) | ![Image](.zefie/benchmarks/melina_kernel_ga4e29e9.jpg?raw=true) | (soon)
[Details](http://browser.geekbench.com/v4/cpu/5472375) | [Details](http://browser.geekbench.com/v4/cpu/5472792)

### [GeekBench Comparison](http://browser.geekbench.com/v4/cpu/compare/5472792?baseline=5472375) (Left is Melina, Right is Stock)
