# ![Tortle Header Image](./Icon.png) Tortle - A tiny utility for Tor

<br />
### Description:
Tortle is a small litle utility for Mac OS X that can easily enable and disable Tor.

Please note that you will need to setup your __torcc__ file. If the path to your __torcc__ file is not __/usr/local/etc/tor/torcc__ you will need to change the variable `torccFile` accordingly.
Also, the default address and port are used __(127.0.0.1:9050)__, so if you normally use a different address/port you must change the variables `proxyAddress` and `proxyPort` accordingly.

<br />
### Installation:
_Tortle requires that you have Tor installed on your system. For instructions on installing Tor, visit [here](https://www.torproject.org/docs/installguide.html)._

__Using `cURL`:__
+ `sudo curl https://raw.githubusercontent.com/thrifus/Tortle/master/tortle -o /usr/bin/tortle; sudo chmod +x /usr/bin/tortle`

__Other installation methods may be implemented later__

<br />
### Usage:
To use Tortle, simply type `tortle` followed by `-e`/`--enable` or `-d`/`--disable`. The arguments should be pretty self explanatory. O_o

<br />
### Notes:
I just threw together the Tortle icon (see attributions below), so it looks kind of strange. If you would like to make an icon for Tortle, please do and email me at <thrifus@gmail.com>

<br />
### Attributions:
+ Turtle icon made by [Freepik](http://www.flaticon.com/authors/freepik) from [Flaticon.com](http://www.flaticon.com/)
+ Turtle icon has been edited, for original icon, please see [here](http://www.flaticon.com/free-icon/big-turtle-_74710)
