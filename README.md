# i3 config files

This repo contains my configuration files of my i3 window manager.

![pic](https://github.com/Kevincastillo98/i3-config-files/blob/master/i3.png)

## My config file


In order to display status info in the bar, you can do something
  like this in your `.xinitrc`:
  
  ```sh
      while xsetroot -name "`date` `uptime | sed 's/.*,//'`"
      do
          sleep 5
      done &
      exec dwm
  ```
