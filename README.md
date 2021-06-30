# rwwyoyt (Random Words When you Open your Terminal:)
![preview](https://raw.githubusercontent.com/Sidmaz666/rwwyoyt/main/rw-preview.jpg)
### What it does?
It is a very simple script that takes random words from the rw.txt file and show it to you. The script is self explaniatory. You can add the path of the script to your .zshrc , .bashrc or .fishrc(Not sure about that) file and can have random words shown to you every time when you open your terminal.
## Dependencies
It is not a dependant script :( it relies on a few packages. If you haven't installed these packages the script will not work as intended. The following dependencies are as follows.
1. shuf
2. lolcat
3. figlet
4. figlet-extra-fonts
5. BASH SHELL (Will work on zsh, might work on fish, dash etc)
## Installation
Grab the dependencies, and than copy the rwwyoyt folder to any directory you want, after that just add the path of the script to your .bashrc or .zshrc file. For example.
 /home/$USER/.config/scripts/rwwyoyt/rw-simp.sh
  1. To know if shuf is installed on your distro run the shuf command and check, it is mostly installed in all GNU/Linux distros.
  2. sudo apt-get install lolcat figlet // For Ubuntu and debian based distros
  3. snap install lolcat figlet // Native packages might be old you I will reccomend you to install it using snap :'(
  4. Get the figlet-extra-fonts from git https://github.com/xero/figlet-fonts.git (Though ou only need the 3d.ttf font)
  5. Copy the fonts to /usr/local/shre/fonts or /usr/share/fonts/ or .local/share/fonts  directory.(Not sure about it 😅)
  6. For Arch based distro just type sudo pacman -S figlet lolcat
  7. For the fonts get it from git or install it using AUR helper like yay :) the package name is figlet-fonts-extra, the command you will type on your terminal will be yay -S figlet-fonts-extra.
### Note
Only three lines of code, it loads relatively fast doesn't lag, you can customize the rw.txt file with your own preferences of words you wanna see :)
