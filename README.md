# Firefox 3 Theme

This is a theme for Firefox Quantum ***PROTON*** (89 to latest version) to look like Firefox 3.
This theme has only been tested on versions 115esr and 128esr, it should work on older or newer versions.
If it has an issue with newer versions, raise an issue. If it has an issue with older versions (pre-115), don't bother. It will not be fixed.

This borrows mostly from *Aris-t2/CustomCSSForFX* and very slightly from *echelon-theme/echelon*. Licensed under GPL 3.0 and MPL 2.0.
If you are looking for the Firefox Quantum 57-88 ***PHOTON*** version of this theme, go to https://github.com/OmegaAOL/Firefox3Theme/

I ***highly*** recommend you to read the Q&A section further down. You might find a theme or even a browser that suits your needs better.

# Requirements

**YOU MUST HAVE FIREFOX 89 OR ABOVE!!!**
**WILL NOT WORK ON PROTON-ERA "SQUARE TABS" FIREFOX BROWSERS (v88 AND LOWER) OR NON-QUANTUM "CLASSIC" FIREFOX BROWSERS (v56 AND LOWER)**

**1)** Download the Latest Release - includes the ***chrome*** folder.

**2)** Install the Mozilla Color theme ***Firefox 3 Classic***: https://addons.mozilla.org/en-US/firefox/addon/firefox-3-classic/

**3)** Make sure you have the following set: 

toolkit.legacyUserProfileCustomizations.stylesheets > *True*

browser.compactmode.show > *True*

*(type in ***about:config*** in the URL bar, search for the config rule in the page, and click the toggle button to the right to set to True)*
If any one of these are not there already, type them in the bar > at the bottom, check *Boolean* > click the plus icon to the right.

**4)** Go to the Customize Toolbar page (right-click on empty space on tab bar > Customize Toolbar). Set Bookmarks Toolbar to ***Always Show***, set Density to ***Compact - not supported***,
check the ***Menu Bar*** checkbox and check the ***Title Bar*** checkbox. This helps fix spacing issues in the Mozilla color theme.
You must also add at least one bookmark to the Bookmarks Toolbar to keep it visible if you haven't enabled it before.
If you see the Mozilla default bookmarks (e.g: "Getting Started") already present, *this is not necessary.*

*Optional:* Enable the Search Bar and drag it to the right of Address Bar. Put Zoom Controls to the right of Search Bar. Enable Home Button and Reload button in Customize Toolbar and place them like this: BACK - FORWARD - RELOAD - HOME

**5)** Type in ***about:profiles*** in the URL bar. Find the profile marked *This is the profile in use and it cannot be deleted* and click on the TOPMOST ***Open Folder*** button below it (for Root Directory).
A Windows Explorer/Finder/etc window will open. Copy and paste the ***chrome*** folder to this directory. Go back to the ***about:profiles*** page and click ***Restart Firefox.***

**6)** That's it for now - unless you're running *Firefox ESR*, make sure to disable auto-updates by going to Menu Bar > Tools > Settings > search for *Firefox Updates* > change to ***Check for updates but let you choose to install them.***
If you choose to update, the theme may randomly break, making it look unsightly or (in most cases) making Firefox unusable.





# YouTube Theme (Optional)

Install a few addons:

YouTube Redux @ https://addons.mozilla.org/en-US/firefox/addon/youtube-redux/

Annotations Restored @ https://addons.mozilla.org/en-US/firefox/addon/annotations-restored

Return YouTube Dislikes @ https://addons.mozilla.org/en-US/firefox/addon/return-youtube-dislikes/

I recommend fiddling with the default Redux settings to achieve your preferred look. This is non-invasive and not a custom hosted video page unlike some options.
The other options are *slow, buggy, and lack a ton of features*. If you really want the 2008 look and not Youtube Redux's 2013-2017 theming, check out https://vorapis.pages.dev/



# Questions and Answers (Q&A)

***I don't want the Menu Bar/Bookmarks Toolbar.***

Sorry, they were on by default in Firefox 3 and most theme components (Mozilla color theme, TabsOnBottom) don't work properly without them.

***Not an exactly accurate recreation of Firefox 3. Some elements look modern and some elements are from different versions of Firefox.***

If you want accuracy, you can use Echelon (echelon-theme/echelon) instead. This, however, slowed down my browser's speed. Unlike Echelon, this theme
uses almost no JavaScript, except for changing the home/newtab page and the Bookmarks/History Library. You should not expect any dips in speed.
The Native Controls Patch is also not listed here due to a dip in scrolling speed I observed when using it.

In addition, Echelon only supports Firefox from 115 and upwards - the older version of this theme supports all old versions of Firefox Quantum Photon,
and the new version of this theme supports all versions of proton. Both theme versions in combination support all versions of Quantum from 57 to 136
spanning a Firefox release history of over 7 years.

***I prefer classic Firefox/old Quantum Firefox!***

For users of XUL-based "classic" Firefox versions, *Classic Theme Restorer* is a good extension for you. For users of old Quantum-based Photon Firefox, you can make use of the
old theme here: *https://github.com/OmegaAOL/Firefox3Theme*

Before you do this, if you are intent on using an older Gecko-based and XUL-addon supporting Firefox version, I highly recommend ***Pale Moon*** with the ***Aeromoon*** theme for a pixel-perfect Firefox 3 look while also being fast and compatible with nearly all modern sites.
*Pale Moon* can be downloaded at https://palemoon.org/ and *Aeromoon* can be installed at https://addons.palemoon.org/addon/aeromoon/

***Why not just use Firefox 3 instead of settling for a cobbled-together, subpar theme?***

I really do hope nobody is considering this. Firefox 3 was released almost 17 years ago. If you really want Firefox 3, you may download it from Mozilla for 32-bit Windows,
32-bit OS X, and 32-bit Linux at https://ftp.mozilla.org/pub/firefox/releases/3.6.9/

For perfectionists, I highly recommend ***Pale Moon*** with the ***Aeromoon*** theme for a pixel-perfect Firefox 3 look while also being fast and compatible with nearly all modern sites.
*Pale Moon* can be downloaded at https://palemoon.org/ and *Aeromoon* can be installed at https://addons.palemoon.org/addon/aeromoon/

***Didn't work - my Firefox is now broken! Thanks a lot.***

You should have used a *recommended* version of Firefox. My current recommendation is 128ESR, although 115ESR is also fine.
Delete the compatibility.ini file in the profile folder, make a backup of the folder, uninstall Firefox, reinstall Firefox 128 from "https://ftp.mozilla.org/pub/firefox/releases/128.8.0esr/",
paste the folder back where it was if it has been deleted, restart Firefox, if it hasn't used the same profile go to about:profiles and set your profile as the default. It should work now.












