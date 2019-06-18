# i3 config files

This repo contains my curent configuration file and my i3 status bar.

![pic](https://github.com/Kevincastillo98/i3-config-files/blob/master/i3.png)

## An overview

This configuration files are alocated in `/etc/i3/config` and  `/etc/i3status`

`.xinitrc`:
  
  ```sh
      while xsetroot -name "`date` `uptime | sed 's/.*,//'`"
      do
          sleep 5
      done &
      exec dwm
  ```
