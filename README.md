# ARM-Full-system SIMULATION IN gem5
 ubuntu 18.04
 Gem5 version- Version 21.2.1.1
 
 Download files. Set path to binaries using "export".
 eg: export M5_PATH=/home/tuna/Desktop/life/gem5/fs_images

Simulation
--------------------------

 build/ARM/gem5.opt configs/example/fs.py 
 --bootloader="$M5_PATH/boot_v2.arm64"
 --kernel="$M5_PATH/vmlinux.arm64" 
 --disk="$M5_PATH/ubuntu-18.04-arm64-docker.img"
