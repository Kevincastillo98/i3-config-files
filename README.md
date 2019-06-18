# i3 config files

This repo contains my curent configuration file and my i3 status bar.

![pic](https://github.com/Kevincastillo98/i3-config-files/blob/master/i3.png)

## An overview

This configuration files are located by default in `/etc/i3/config` and  `/etc/i3status`
`.config`:
  
  ```
      bindsym  $mod+F2 exec iceweasel
      bindsym  $mod+F3 exec pcmanfm
      bindsym  $mod+x  exec  morc_menu
      bindsym  $mod+q  exec  i3lock
      bindsym  $mod+t  exec telegram
      bindsym  $mod+i  exec scrot
      bindsym  $mod+n exec  ranger
      exec_always  feh --bg-scale  /home/kevin/Imágenes/Wallpapers/Difuso.png
      exec_always  nm-applet
      exec_always  volumeicon
  ```
