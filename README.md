# ARM-Full-system SIMULATION IN gem5
 ubuntu 18.04
 Gem5 version- Version 21.2.1.1
image file:  https://drive.google.com/file/d/1-G29ConJz3a6g13YNm2pbXUZjtRKkVJG/view?usp=sharing
 Download the files bootloader,kernel and disk. Set path to full system images using "export".
 
 eg: export M5_PATH=/.../fs_images

Simulation
--------------------------

 build/ARM/gem5.opt configs/example/fs.py 
 --bootloader="$M5_PATH/boot_v2.arm64"
 --kernel="$M5_PATH/vmlinux.arm64" 
 --disk="$M5_PATH/ubuntu-18.04-arm64-docker.img"
