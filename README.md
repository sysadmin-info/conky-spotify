# conky-spotify
Fork of https://github.com/Aaahh/conky-spotify

![Screenshot](/screenshot.png?raw=true "Screenshot")

This is a spotify display made for the native spotify client:
https://www.spotify.com/us/download/previews/

Dependencies:
* conky
* git to clone the resource
* python 
* http://www.dafont.com/ll-record.font (for the play symbol)
* https://www.dafont.com/roboto.font (for displaying artist and album name)
* imagemagick
* Unity or Gnome (otherwise use branch v1.0)

```
cd .conky
git clone https://github.com/sysadmin-info/conky-spotify
cp conkyrc ~/
cd ..
mv conkyrc .conkyrc
conky -c ~/conkyrc
Add conky to autostart
```

=========================================
Forked and adapted to modern version by Sysadmin-info

Forked by Aaahh Ahh

Originally Created by Moxew:
http://moxew.deviantart.com/
