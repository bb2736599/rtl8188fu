RTL8188FU driver for Linux kernel 4.15.x ~ 6.0.x (Linux Mint, Ubuntu or Debian Derivatives)

info: rtl8188fu support will be add to rtl8xxxu module of Linux kernel. https://patchwork.kernel.org/project/linux-wireless/patch/b14f299d-3248-98fe-eee1-ba50d2e76c74@gmail.com/
# How to install
sudo apt-get install build-essential git dkms linux-headers-$(uname -r)
git clone https://github.com/kelebek333/rtl8188fu

sudo dkms install ./rtl8188fu

sudo cp ./rtl8188fu/firmware/rtl8188fufw.bin /lib/firmware/rtlwifi/
# Configuration
