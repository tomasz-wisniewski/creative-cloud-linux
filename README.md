# Creative Cloud for PlayOnLinux

This is an install script for [Adobe Creative Cloud](https://www.adobe.com/creativecloud.html), designed to be used with [PlayOnLinux](https://www.playonlinux.com). This downloads and installs the Creative Cloud software from Adobe's website. Once setup is completed, you can use the Adobe Application Manager to download and install Photoshop, Dreamweaver, Illustrator, and other apps.

![Adobe Application Manager](https://i.imgur.com/MSIIpdt.png)

A (free) Adobe ID is required to install additional applications. Most Adobe applications require [a paid subscription](https://www.adobe.com/creativecloud/plans.html).

**NOTE:** Only Application Manager, Photoshop CC 2015, and Lightroom 5 have been extensively tested.

## How to use this script

1. Download PlayOnLinux from your distribution's package manaer (e.g. Ubuntu Software Center) or from [the PlayOnLinux website](https://www.playonlinux.com/en/download.html).
2. Save the install script to your computer.
3. Open PlayOnLinux, go to Tools > Run a local script
4. Select the install script you just downloaded

After the setup process is finished, you can open Adobe Application Manager from PlayOnLinux to download and install the apps you need.

## Background info

I made this script because getting Creative Cloud working in Wine is pretty difficult, thanks to multiple versions of the setup program being available from Adobe's website that vary in compatibility with Wine. I found that the Creative Cloud setup program from the Photoshop download page works best in Wine ([direct link](https://ccmdls.adobe.com/AdobeProducts/PHSP/18_1_1/win32/AAMmetadataLS20/CreativeCloudSet-Up.exe)), especially when the OS is temporarily set to Windows XP. That's the version that this script uses, if you choose to let the script download the program for you.

After Creative Cloud is done installing, the script reverts the OS version back to Windows 7, so newer Adobe apps (like Photoshop CC 2015) can be downloaded through Application Manager.

---------------------------------------

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
