# Firefox 3 Theme

This is a theme for Firefox Quantum ***PROTON*** (89 to latest version) to look like Firefox 3.
This theme has only been tested on versions 115esr and 128esr, it should work on older or newer versions.
If it has an issue with newer versions, raise an issue. If it has an issue with older versions (pre-115), don't bother. It will not be fixed.

**I recommend you use Firefox 128esr, or 115esr if you're on Windows 7! Features may not fully work on other versions - it should be compatible on paper, but has been sparingly tested.**

This borrows majorly from ***Aris-t2/CustomCSSForFX*** and very slightly from ***echelon-theme/echelon***. Licensed under GPL 3.0 and MPL 2.0.
If you are looking for the Firefox Quantum 57-88 ***PHOTON*** version of this theme, go to https://github.com/OmegaAOL/Firefox3Theme/

I ***highly*** recommend you to read the Q&A section further down. You might find a theme or even a browser that suits your needs better.

# Windows Requirements (Windows XP, Windows 7 to 11)

Windows 7, Windows 8: 115esr (last supported version, tested OK)

Windows 10, Windows 11: 128esr (tested OK)

Other users can look at my old repo.

# Download Firefox

115esr and 128esr are tested working.

**128ESR** (select your platform and language region in the directory, default win64 -> en-US -> Firefox Setup XX.XXXX.XX.exe)

https://ftp.mozilla.org/pub/firefox/releases/128.9.0esr/

**115ESR** (select your platform and language region in the directory, default win64 -> en-US -> Firefox Setup XX.XXXX.XX.exe)

https://ftp.mozilla.org/pub/firefox/releases/115.22.0esr/

You can use your existing, newer, Firefox installation (features may or may not be broken, try it out if you want to), or you can:

1) uninstall the later version of Firefox
2) delete compatibility.ini in your default profile folder
3) install and launch 115 or 128 esr


If this has problems, you should ideally create a new profile.

If you are going to install this theme on a Firefox installation newer than 128ESR, I would **highly** recommend you to disable Firefox auto-updates. Search
for them in Settings.

# Requirements

**YOU MUST HAVE FIREFOX 89 OR ABOVE AT A MINIMUM, AND SUPPORT IS ONLY OFFERED FOR FIREFOX 115ESR AND ABOVE!!!** *(Download links for 115 and 128ESR above)*

**WILL NOT WORK ON PROTON-ERA "SQUARE TABS" FIREFOX BROWSERS (v88 AND LOWER) OR NON-QUANTUM "CLASSIC" FIREFOX BROWSERS (v56 AND LOWER)**

**FIREFOX FORKS LIKE MULLVAD BROWSER, ZEN BROWSER, OR LIBREWOLF ARE NOT EXPECTED OR GUARANTEED TO WORK WITH THIS THEME.** Nevertheless, you can try if the fork is based on Firefox 115 or above and
doesn't have it's own custom theme.

*Firefox forks that are supported by this theme are: Marble. r3dfox and Mullvad were supported but are no longer due to theming changes from standard Firefox.*

**1)** Download the Latest Release of this theme from the Releases section - includes the ***chrome*** folder.

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

First - if you have any custom userscripts or userstyles that modify YouTube, disable them before this.

Install Greasemonkey or Tampermonkey - I recommend Greasemonkey.

Go to https://vorapis.pages.dev/#/home/download and click "Install V3 as userscript"

Go to https://greasyfork.org/en/scripts/485622-startube and click the green "Install" button

Restart Firefox, open YouTube, and configure StarTube to your liking. For an era-appropiate theme (Firefox 3.6 was released early 2010), select Stargazer (late 2009).

# Other add-ons I recommend to complete the experience 

Old Reddit Redirect @ https://addons.mozilla.org/en-US/firefox/addon/old-reddit-redirect/ - tells Reddit to display its older layout.
Does not modify anything. 

Old Twitter @ https://addons.mozilla.org/en-US/firefox/addon/old-twitter-layout-2024/ - old layout for Twitter. Custom hosted frontend (I think).

Old Facebook @ https://addons.mozilla.org/en-US/firefox/addon/old-layout-for-facebook/ - tells Facebook to display the old layout. Modifies nothing.

Tampermonkey with the "Gplex" script @ https://greasyfork.org/en/scripts/492193-gplex-old-google-frontend - old Google layout(s). Custom hosted frontend. Image previews broken.

uBlock Origin @ https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/ - not a part of making Firefox more nostalgic, but it's vital for a Web user and really should be bundled in with Firefox at this point

# Questions and Answers (Q&A)

***I don't want the Menu Bar/Bookmarks Toolbar.***

Sorry, they were on by default in Firefox 3 and most theme components (Mozilla color theme, TabsOnBottom) don't work properly without them.

***Not an exactly accurate recreation of Firefox 3. Some elements look modern and some elements are from different versions of Firefox.***

If you want accuracy, you can use Echelon (echelon-theme/echelon) instead. This, however, slowed down my browser's speed. Unlike Echelon, this theme
uses almost no JavaScript, except for changing the home/newtab page and the Bookmarks/History Library. You should not expect any dips in speed.
The Native Controls Patch is also not listed here due to a dip in scrolling speed I observed when using it.

In addition, Echelon only supports Firefox from 115 and upwards - the older version of this theme supports all old versions of Firefox Quantum Photon,
and the new version of this theme supports all versions of proton. Both theme versions in combination support (on paper) all versions of Quantum from 57 to 131
spanning a Firefox release history of over 7 years. 

***I prefer classic Firefox/old Quantum Firefox!***

For users of XUL-based "classic" Firefox versions, *Classic Theme Restorer* is a good extension for you. For users of old Quantum-based Photon Firefox, you can make use of the
old theme here: *https://github.com/OmegaAOL/Firefox3Theme*

Before you do this, if you are intent on using an older Gecko-based and XUL-addon supporting Firefox version, I highly recommend ***Pale Moon*** with the ***Aeromoon*** theme for a pixel-perfect Firefox 3 look while also being fast (enough) and compatible with nearly all modern sites.
*Pale Moon* can be downloaded at https://palemoon.org/ and *Aeromoon* can be installed at https://addons.palemoon.org/addon/aeromoon/

***Why not just use Firefox 3 instead of settling for a cobbled-together, subpar theme?***

I really do hope nobody is considering this. Firefox 3 was released almost 17 years ago. If you really want Firefox 3, you may download it from Mozilla for 32-bit Windows,
32-bit OS X, and 32-bit Linux at https://ftp.mozilla.org/pub/firefox/releases/3.6.9/

For perfectionists, I highly recommend ***Pale Moon*** with the ***Aeromoon*** theme for a pixel-perfect Firefox 3 look while also being fast (enough) and compatible with nearly all modern sites.
*Pale Moon* can be downloaded at https://palemoon.org/ and *Aeromoon* can be installed at https://addons.palemoon.org/addon/aeromoon/

***Didn't work - my Firefox is now broken! Thanks a lot.***

You should have used a *recommended* version of Firefox. My current recommendation is 128ESR, although 115ESR is also fine.
Delete the compatibility.ini file in the profile folder, make a backup of the folder, uninstall Firefox, reinstall Firefox 128 from "https://ftp.mozilla.org/pub/firefox/releases/128.8.0esr/",
paste the folder back where it was if it has been deleted, restart Firefox, if it hasn't used the same profile go to about:profiles and set your profile as the default. It should work now.

***If you recommend Pale Moon, why don't you use it?***

Good question. I use Firefox because it's faster *(Pale Moon is based on Firefox 33 and has a LOT of code from older versions, including a major chunk from... Firefox 3!)* and has multiprocess mode.
It also supports the extensions I like and since I do some web development it's a must-have.

Pale Moon however is able to render modern sites and is patched with security updates.










