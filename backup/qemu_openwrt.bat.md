```
qemu-system-aarch64.exe -m 2048m -boot c -M virt ^
-nic user -nic user -cpu cortex-a53 -smp 4 ^
-hda "T:\down\openwrt-23.05.3-armsr-armv8-generic-ext4-combined.img\openwrt-23.05.3-armsr-armv8-generic-ext4-combined.img" ^
-nographic
```