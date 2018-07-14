# MobileAdTrackers
Taken from DNS logs, formatted in hostfile and other formats.

Caveat: This will also block game reward systems like Tapjoy (i.e. watch videos and play other games for points)

Tools and other people interested in Android mobile privacy efforts:

To give you an idea of why we need better mobile ad lists take a look at [Marketing Technology Landscape Supergraphic - Martec](https://chiefmartec.com/2018/04/marketing-technology-landscape-supergraphic-2018/).  Each year they release a new poster and you can see the growth of the mobile marketing landscape over the past several years.  Most host-based blocklists do not target mobile ad networks- possibly because they monitor desktop and desktop browser traffic.  Adaway for Android has a built-in hostfile of mobile ad networks but [it hasn't been updated](https://github.com/AdAway/adaway.github.io/commits/master/hosts.txt) since 2016.  The last attempt was by me and it was reverted as I had mistakenly included URL shortener goo.gl.

This list is a heck of a lot more scrutinized than Adaway's as I log from my device and always see what apps are doing out of curiousity.  Not only that, someone used a utility called Funceble that checks host files for dead hosts and approx. [41% of the Adaway list](https://github.com/AdAway/adaway.github.io/pull/8) - a list designed to target mobile ad networks - no longer exist.  I criticize only because you're still letting through what you wanted to prevent.  The other popular lists out there are fine for blocking desktop and browser-based ad networks but I rarely see those domains and subdomains get hit by mobile apps unless they are a web browser app or the app is essentially a webpage packaged as an app.


|Utilities & Resources|
|---|
|[Koodous](https://koodous.com/apks) - [Play Store](https://play.google.com/store/apps/details?id=com.koodous.android) [Github](https://github.com/Koodous)|
|[Exodus Privacy](https://exodus-privacy.eu.org/) - [Github](https://github.com/Exodus-Privacy)|
|[Yale Privacy Lab](https://privacylab.yale.edu) - [Github](https://github.com/YalePrivacyLab)|
|[Lumen Privacy Monitor (formerly Project Haystack) - ICSI UC Berkeley](https://www.haystack.mobi/) - [Play Store](https://play.google.com/store/apps/details?id=edu.berkeley.icsi.haystack)|
|[Protect My Privacy(PMP) - Carnegie Mellon/Synergy Labs](http://www.android.protectmyprivacy.org) - [XPosed Repo](http://repo.xposed.info/module/org.synergylabs.pmpandroid)|
|[Recon (Northeastern University)](https://recon.meddle.mobi)|
|[NetGuard](https://www.netguard.me/) - [Play Store](https://play.google.com/store/apps/details?id=eu.faircode.netguard) [Github](https://github.com/M66B/NetGuard)|
|[XprivacyLua/Pro](https://lua.xprivacy.eu/)  [Play Store](https://play.google.com/store/apps/details?id=eu.faircode.xlua.pro)/[Xposed Repo](http://repo.xposed.info/module/eu.faircode.xlua) [Github](https://github.com/M66B/XPrivacyLua)|
|Dexplorer - [Play Store](https://play.google.com/store/apps/details?id=com.dexplorer)|
|My Android Tools(Pro) - [Play Store](https://play.google.com/store/apps/details?id=cn.wq.myandroidtoolspro) dead link. find the free version on [apkmirror](https://www.apkmirror.com/apk/wangqi/my-android-tools/)|
|[Inspeckage - Package Inspector](http://ac-pm.github.io/Inspeckage/) - [Play Store](https://play.google.com/store/apps/details?id=mobi.acpm.inspeckage)/[XPosed Repo](http://repo.xposed.info/module/mobi.acpm.inspeckage) [Github](https://github.com/ac-pm/Inspeckage)|
|[PyFunceble](https://funilrys.github.io/PyFunceble/) - [Github](https://github.com/funilrys/PyFunceble)|
|[FilterLists.com](https://filterlists.com) - [Github](https://github.com/collinbarrett/FilterLists|

License: You can do whatever you want with this host file.  I put it out here for others to use and for me to have a place to put it.
