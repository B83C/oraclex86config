# Optimized kernel config for Oracle Cloud free tier x86_64

This repo contains a trimmed down, initrd/initramfs-less, module-less kernel config optimized for oracle cloud free tier x86_64 KVM machines.

Assumed hardware/software:
  - AMD Processor
  - KVM Guest
  - 1/8 OCPU
  
Warning: This kernel config has disabled support for initramfs. Enable manually if needed. 
                            ^ ^ ^
        (meaning you need to enable for use in alpine)
        
Current config : config
Kernel version : 5.15.0-rc4+
  
