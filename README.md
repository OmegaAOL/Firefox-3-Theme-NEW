# Firefox 3 Theme

This is a theme for Firefox Quantum "PROTON" (89 to latest version) to look like Firefox 3.
This theme has only been tested on versions 115esr and 128esr, it should work on older or newer versions.
If it has an issue with newer versions, raise an issue. If it has an issue with older versions (pre-115), don't bother. It will not be fixed.

This borrows mostly from Aris-t2/CustomCSSForFX and very slightly from echelon-theme/echelon. Licensed under GPL 3.0 and MPL 2.0.
If you are looking for the Firefox Quantum 57-88 "PHOTON" version of this theme, go to https://github.com/OmegaAOL/Firefox3Theme/

# Requirements

**YOU MUST HAVE FIREFOX 89 OR ABOVE!!!**
**WILL NOT WORK ON PROTON-ERA "SQUARE TABS" FIREFOX BROWSERS (v88 AND LOWER) OR NON-QUANTUM "CLASSIC" FIREFOX BROWSERS (v56 AND LOWER)**

**1)** Download the Latest Release - includes the ***chrome*** folder.

**2)** Install the Mozilla Color theme ***Firefox 3 Classic***: https://addons.mozilla.org/en-US/firefox/addon/firefox-3-classic/

**3)** Make sure you have the following set: 

toolkit.legacyUserProfileCustomizations.stylesheets > *True*

browser.compactmode.show *True*

*(type in ***about:config*** in the URL bar, search for the config rule in the page, and click the toggle button to the right to set to True)*
If any one of these are not there already, type them in the bar > at the bottom, check *Boolean* > click the plus icon to the right.

**4)** Go to the Customize Toolbar page (right-click on empty space on tab bar > Customize Toolbar). Set Bookmarks Toolbar to ***Always Show***, check the ***Menu
Bar*** checkbox and check the ***Title Bar*** checkbox. This helps fix spacing issues in the Mozilla color theme.
You must also add at least one bookmark to the Bookmarks Toolbar to keep it visible if you haven't enabled it before.
If you see the Mozilla default bookmarks (e.g: "Getting Started") already present, *this is not necessary.*

*Optional:* Enable the Search Bar and drag it to the right of Address Bar. Put Zoom Controls to the right of Search Bar. Enable Home Button and Reload button in Customize Toolbar and place them like this: BACK - FORWARD - RELOAD - HOME

**5)** Type in ***about:profiles*** in the URL bar. Find the profile marked *This is the profile in use and it cannot be deleted* and click on the TOPMOST ***Open Folder*** button below it (for Root Directory).
A Windows Explorer/Finder/etc window will open. Copy and paste the ***chrome*** folder to this directory. Go back to the ***about:profiles*** page and click ***Restart Firefox.***

**6)** That's it for now - unless you're running *Firefox ESR*, make sure to disable auto-updates by going to Menu Bar > Tools > Settings > search for *Firefox Updates* > change to ***Check for updates but let you choose to install them.***
If you choose to update, the theme may randomly break, making it look unsightly or (in most cases) making Firefox unusable.





# YouTube Theme (Optional)

Install the Stylus add-on and import the .json file in the repository. Then go to YouTube and enable all the styles from Stylus.

Install YouTube Redux and enable these: 

![this](redux1.png) ![this](redux2.png)

Install Youtube - Right Side Description userscript from GreasyFork (google it) into Greasemonkey (an add-on for Firefox)




# Questions and Answers (Q&A)

*I don't want the Menu Bar/Bookmarks Toolbar.*
Sorry, they were on by default in Firefox 3 and most theme components (Mozilla color theme, TabsOnBottom) don't work properly without them.

*Not an exactly accurate recreation of Firefox 3.*
Some components are 
*But Firefox 88 doesn't load websites nowadays!*
In about:config, create a string titled 'general.useragent.override' and set its value to the newest Firefox useragent.

*Why doesn't this work on Firefox 89+?*
Firefox 89 completely changed the base UI. As a result, this theme is broken.

*Why doesn't the YouTube theme work?*
Things change over time. I will try to keep the Youtube theme updated.

*Youtube Redux isn't working/is broken!*
YouTube Redux does not get many updates nowadays. Things might be broken. I cannot control these as I do not develop the extension.









