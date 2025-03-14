# iptvscan
Python script for scanning multicast IPTV and saving playlist.

The multi-threaded version scans faster, but it is not well-tested.

## How to use
- First of all, make sure that the channels you want to scan are provided using [multicast](https://en.wikipedia.org/wiki/Multicast_address) IPTV technology.
Even if someone calls it IPTV, it doesn't mean it is. If you don't know what technology is used, then it's most likely not multicast IPTV.
At this point it is an outdated technology and I find it strange to hear that it is still used anywhere today.

- Next, you need to know at least one IP address and port with working IPTV. The script will allow you to scan other channels.
If first number in IP adress less 224 - this not multicast IPTV.

- Install python version 3 from https://www.python.org/downloads/

- Open iptvscan.py in text editor and edit variables ip_start, ip_end and list of ports.

- Run iptvscan.py

## Thank you for using
If you like this script, please consider donating. 

https://ko-fi.com/joddude
