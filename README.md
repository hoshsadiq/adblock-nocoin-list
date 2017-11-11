# NoCoin adblock list
This is an adblock list to block "browser-based crypto mining."
Currently there are a few websites added into the lists. If you see other websites supporting these deeds, then feel free to raise an **Issue** or **Pull request** for it to be taken care of.

## Installation

### AdBlock Filter
Make sure you have an adblocker installed in your desktop or mobile browsers that uses [Adblock Plus](https://adblockplus.org/)' filter list:
* ![AdB](https://i.imgur.com/3KbyifF.png) [AdBlock](https://getadblock.com)
* ![ABP](https://i.imgur.com/kPRCfhu.png) [Adblock Plus](https://adblockplus.org/)
* ![uBo](https://i.imgur.com/PSFuzKb.png) [uBlock Origin](https://github.com/gorhill/uBlock)
* ![Adb Browser](https://i.imgur.com/6pkmjA0.png) [Adblock Browser](https://adblockbrowser.org/) for **Android** and **iOS** devices

Then import below link into your adblocker:
- [https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/nocoin.txt](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/nocoin.txt)

### 1Blocker
You can also use the 1blocker package if you use <img src="https://1blocker.com/img/icon.png" width=16> [1Blocker](https://1blocker.com) on iOS or Mac.
Simply open the file in 1Blocker on iOS or MacOS to import it.
- https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/nocoin.1blockpkg

# Hosts based blocking
For the blocking based on the [HOSTS file](https://en.wikipedia.org/wiki/Hosts_(file)) use the below link:
- [https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt)

### hosts
You can simply copy and paste the contents of above file into your hosts file. The locations of your hosts file depends on your system:
- Linux: `/etc/hosts`
- MacOS: `/etc/hosts`
- Windows: `C:\Windows\System32\drivers\etc\hosts`

Whichever OS you use, you will require escalated privileges to edit the file (either use `sudo` for Linux/MacOS or administrative account on Windows)

### Perimeter blocking
You may use the hosts file with below applications to block these miners on whole networks. Simply add the link to the above hosts file in each system.

* ![pfSense](https://i.imgur.com/ElyO5Ie.png) [pfSense](https://www.pfsense.org/) with [pfBlockerNG](https://www.tecmint.com/install-configure-pfblockerng-dns-black-listing-in-pfsense/)
* ![Pi-hole](https://i.imgur.com/0mgKKma.png) [Pi-hole](https://pi-hole.net)
