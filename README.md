# ![Tortle Header Image](http://i.imgur.com/wsacBIn.png) Tortle - A tiny utility for Tor on OS X

<br />
[![Code Climate](https://aws.codeclimate.com/github/thrifus/Tortle/badges/gpa.svg)](https://aws.codeclimate.com/github/thrifus/Tortle)

[![Issue Count](https://aws.codeclimate.com/github/thrifus/Tortle/badges/issue_count.svg)](https://aws.codeclimate.com/github/thrifus/Tortle)

[![Flattr this][flattr_IMG]][flattr_LINK]
[flattr_IMG]: http://button.flattr.com/flattr-badge-large.png
[flattr_LINK]: https://flattr.com/submit/auto?user_id=thrifus&url=https%3A%2F%2Fgithub.com%2Fthrifus%2FTortle

### Description:
Tortle is a small litle utility for Mac OS X that can easily enable and disable Tor.

Please note that you will need to setup your __torcc__ file. If the path to your __torcc__ file is not __/usr/local/etc/tor/torcc__ you will need to change the variable `torccFile` accordingly.
Also, the default address and port are used __(127.0.0.1:9050)__, so if you normally use a different address/port you must change the variables `proxyAddress` and `proxyPort` accordingly.

<br />
### Installation:
__Using Homebrew (recommended):__
+ `brew tap thrifus/Tortle`
+ `brew install Tortle`

__Using `cURL` to install to `/usr/bin/tortle`:__
+ `sudo curl https://raw.githubusercontent.com/thrifus/Tortle/master/tortle -o /usr/bin/tortle; sudo chmod +x /usr/bin/tortle`

_(Other installation methods may be implemented later)_

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

### License
NO LICENSE
~~This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/.~~
