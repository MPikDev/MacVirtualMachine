# MacVirtualMachine



# Manual Partition
1. root
  1. Type - EXT4
  2. Mount Point - /
  3. Flags - root
  4. Size - How much you need(for Mac at leat 50GB beacause OS is like 16 and if you want to update it will download a 16GB file and need 16gb to export it)
2. boot
  1. Size - 500mb
  2. Type - FAT32
  3. Mount Point - /boot/efi
  4. Flags - bios-grub, boot 
3. Swap
  1. Size - half ur ram
  2. Type - Swap
  3. Flag - Swap

# Install macOS Simple KVM

https://github.com/foxlet/macOS-Simple-KVM

