# all-language-solve-in-debain-


first command , this is for me , and i found this : bangla laguage not support in debian gnome , how can i fix using terminal

 command 1 : sudo apt update && sudo apt install -y locales gnome-language-selector language-pack-bn fonts-beng

 command 2: Generate and Set Bangla Locale, : sudo dpkg-reconfigure locales

command for this , Now, set Bangla as a system language:sudo update-locale LANG=bn_BD.UTF-8

install Bangla Fonts: sudo apt install -y fonts-beng-extra fonts-lohit-beng-assamese fonts-noto-core fonts-noto-extra

if gnome , Restart GNOME Session: gnome-session-quit --logout --no-prompt


sudo reboot
