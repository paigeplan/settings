# settings

wireless driver for latitude
https://mudongliang.github.io/2016/06/29/install-driver-for-wireless-network-adapter-bcm4352.html

### keyboard shorcuts 
audio: 

amixer set Master 5%+

amixer set Master 5%-

amixer -D pulse set Master 1+ toggle 

### print screen: 
xfce4-screenshooter 

### vimrc

set background=dark 

syntax on 

colorscheme desert 

### dropdown term
xfconf-query -c xfce4-keyboard-shortcuts -p /commands/custom/F4 -n -t string -s "xfce4-terminal --drop-down"

screenfetch
