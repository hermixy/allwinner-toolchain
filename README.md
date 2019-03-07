# Get H3 Linux-4.14 BSP toolchain:
```bash
$ cat arm-cortexa9-linux-gnueabihf-4.9.3-20160512.tar.xz* >arm-cortexa9-linux-gnueabihf-4.9.3-20160512.tar.xz
$ tar xf arm-cortexa9-linux-gnueabihf-4.9.3-20160512.tar.xz
```

# Get H5 Linux-4.14 BSP toolchain:
```bash
$ cat gcc-linaro-6.3.1-2017.02-x86_64_aarch64-linux-gnu.tar.xz* >gcc-linaro-6.3.1-2017.02-
x86_64_aarch64-linux-gnu.tar.xz
$ tar xf gcc-linaro-6.3.1-2017.02-x86_64_aarch64-linux-gnu.tar.xz
```

# Get H5/H6 Linux-3.10 BSP toolchain:
```bash
$ cat gcc-linaro-aarch64.tar.xz* >gcc-linaro-aarch64.tar.xz
$ cp gcc-linaro-aarch64.tar.xz h6/lichee/brandy/toolchain/
$ ls gcc-linaro-aarch64.tar.xz gcc-linaro-arm-4.6.3.tar.xz
```

# Add new toolchain to repo:
```
$ split -b 40M toolchain.tar.xz -d -a 1 toolchain.tar.xz
```
