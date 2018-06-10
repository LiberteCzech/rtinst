# rtinst

- This script is made by [arakasi72](https://github.com/arakasi72) with added functions by [Aniverse](https://github.com/Aniverse)
with my modifications and diferent settings.
- My modifications targeting on slow devices, lightweight, greater performance and security.


[Changelog](https://github.com/LiberteCzech/rtinst/wiki/Changelog)

[Performance and security hacks](https://github.com/LiberteCzech/rtinst/wiki/Performance-and-security-hacks)

## Installation

```
bash -c "$(wget --no-check-certificate -qO- https://raw.githubusercontent.com/LiberteCzech/rtinst/master/rtsetup)"
```
```
rtinst -$opinions -v $rtorrentVERSION -u $USERNAME -p $PASSWORD -w $WEBPASSWORD 
```
For install new rtinst
```
rtinst -tflmi -v 0.9.6 -u hermiona -p seB6v4eVar6g4be1Ebv -w w6fF4gaerh4SVs9b  
```
For reinstall if you have upgraded to 0.9.7
```
rtinst -tflmi -v 0.9.7 -u hermiona -p seB6v4eVar6g4be1Ebv -w w6fF4gaerh4SVs9b  
```


- `-t` Do NOT change SSH port  
- `-f` Set FTP port to 21  
- `-y` Force yes to all the questions  
- `-l` Enable logging to ~/rtinst.log  
- `-m` Install the latest master build of rutorrent  
- `-i` Enable IPv6 for rTorrent and libtorrent-rakshasa  
- `-u` Name the user to be primary rtorrent user  
- `-p` Set the unix password  
- `-w` Set the web password for the user  
- `-v` Set the rTorrent version you would like to be installed  


## Modifications

- **New Opinions**  
Using `-i` opinion to enable IPv6 support  
Using `-f` opinion to set FTP port to 21  
Using `-t` opinion to keep the old SSH port  
Using `-v` opinion to select the rtorrent version to be installed  

- **ruTorrent plugins and themes**  
Install club-QuickBox theme  
Install MaterialDesign theme  


- **Enable rTorrent logging**  
- **Tweak rTorrent default settings**  
- **Do NOT disable root login**  
- **Raised open file limits to 666666**  


## Guides

[The original README](https://github.com/arakasi72/rtinst/blob/master/README.md)  
[The detailed user guide](https://github.com/arakasi72/rtinst/wiki/Guide)  
[The detailed installation guide](https://github.com/arakasi72/rtinst/wiki/Installing-rtinst)  
[License](https://github.com/arakasi72/rtinst/blob/master/LICENSE)  
