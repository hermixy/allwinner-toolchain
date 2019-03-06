```
Get H3 Linux-4.14 BSP toolchain:
$ cat arm-cortexa9-linux-gnueabihf-4.9.3-20160512.tar.xz* >arm-cortexa9-linux-gnueabihf-4.9.3-20160512.tar.xz
$ tar xzf arm-cortexa9-linux-gnueabihf-4.9.3-20160512.tar.xz

Get H5 Linux-4.14 BSP toolchain:
$ cat gcc-linaro-6.3.1-2017.02-x86_64_aarch64-linux-gnu.tar.xz* >gcc-linaro-6.3.1-2017.02-x86_64_aarch64-linux-gnu.tar.xz
$ tar xzf gcc-linaro-6.3.1-2017.02-x86_64_aarch64-linux-gnu.tar.xz

Add new toolchain to repo:
$ split -b 40M toolchain.tar.xz -d -a 1 toolchain.tar.xz
```
