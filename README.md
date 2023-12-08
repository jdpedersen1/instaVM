# instaVM
Bash scripts used to build and launch virtual machines without launching a gui tool like Virt-Manager. Just clone repo to desired location on your system, make sure they are executable, and set up a key binding to call

# NOTE 
before using this script, make sure your system is set up for virtualization, there are plenty of tutorials online on how to do this. also verify all dependencies are installed

## Dependencies 
* kvm
* qemu
* virt-vieweri
* devour (https://github.com/salman-abedin/devour)
* virt-manager
    - for backup
* ovmf
    - to allow for uefi 
* notification daemon running (Dunst)
* program launcher (the following are preconfigured in the script)
    - fzf
    - rofi
    - wofi
    - dmenu
* Alacritty (or edit the script to call your preferred terminal emulator)
