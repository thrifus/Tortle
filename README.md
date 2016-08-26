# Tortle - A tiny utility for Tor on OS X

<br />
[![Code Climate](https://aws.codeclimate.com/github/thrifus/Tortle/badges/gpa.svg)](https://aws.codeclimate.com/github/thrifus/Tortle)

[![Issue Count](https://aws.codeclimate.com/github/thrifus/Tortle/badges/issue_count.svg)](https://aws.codeclimate.com/github/thrifus/Tortle)

### Description:
Tortle is a small litle utility for Mac OS X that can easily enable and disable Tor.

Please note that you may need to setup your __torcc__ file. If the path to your __torcc__ file is not __/usr/local/etc/tor/torcc__ you will need to change the variable `torccFile` accordingly.

<br />
### Installation:
__Using Homebrew (recommended):__
+ `brew tap thrifus/Tortle`
+ `brew install Tortle` (if you don't already have Tor installed with Homebrew, use `--with-tor` to install it)

__Using `cURL` to install to `/usr/bin/tortle`:__
+ `sudo curl https://raw.githubusercontent.com/thrifus/Tortle/master/tortle -o /usr/bin/tortle; sudo chmod +x /usr/bin/tortle`

_(Other installation methods may be implemented later)_

<br />
### Usage:
To use Tortle, simply type `tortle` followed by either `-e`, `--enable`, or `on` to enable Tortle, or `-d`, `--disable`, or `off` to disable Tortle.

<br />
### License
NO LICENSE
~~This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/.~~
