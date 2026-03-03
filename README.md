# ⚠️ This is a Work-in-progress (WIP)



## 📌 Important

- Mainly for **English** language
- I **VERY** rarely update my browser
- Have not moved everything that could be tweaked to main two `.css` files yet
- `Colours` are borderline set in stone; unless you're willing to tweak them to your liking, this is not perfect.
- I do not use nor recommend [Firefox](<https://www.firefox.com/en-GB/?utm_campaign=SET_DEFAULT_BROWSER>) & [Firefox Developer Edition](<https://www.firefox.com/en-GB/channel/desktop/developer/>) with default configuration (BetterFox `user.js`) 



## 📥 How to install


**about:config**:  
- Set `svg.context-properties.content.enabled` to `true`
- Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`  
**Ones I like (use at own "risk")**:  
- `dom.serviceWorkers.enabled` - Disables Service Workers
- `ui.key.menuAccessKeyFocuses` - **Doesn't** focus menu bar with ALT key
- `xpinstall.signatures.required` - Install ANY extension without signature warning
- `browser.sessionstore.restore_pinned_tabs_on_demand` - **Doesn't** load Pinned tabs on browser startup

**about:profiles**:  
- `Open Folder` of your Root Directory profile (hit the button)
- Drop the `chrome` folder into it & `user.js` file if it exists here



## 💫 Features (More to come?)

- One-line support
- Custom compact Window Buttons
- Colour coded tabs with compact unloaded
- *Hopefully* clean imports + code to know exactly what does what



## 📄 Information

### 🔨 Harden Firefox
- ⭐ [Betterfox](<https://github.com/yokoffing/Betterfox>)
- [arkenfox](<https://github.com/arkenfox/user.js>)

### 🌐 Browsers
- ⭐ [LibreWolf](<https://librewolf.net/>)
- [Waterfox](<https://www.waterfox.com/>)

### 📦 Import (Probability of changing)

#### **Add `/` to start of `url` to cancel import**:  
`userChrome.css`  
```css
@import url("URL Imports/Square Everything.css");
@import url("URL Imports/Extension Panel dropdown.css");
/* Tabs / Toolbar (top) */
@import /url("URL Imports/One-Liner.css");
@import url("URL Imports/Window Buttons.css");
@import /url("URL Imports/Extreme Compact Tabs.css"); /* Set `ui.tooltip.delay_ms`: `0` | instant tooltip for my settings */
@import url("URL Imports/Compact Discard + Colored coded tabs.css");
```
`userContent.css`  
```css
@import url("URL Imports/New-Tab.css");
@import url("URL Imports/Setting & Addons.css");
@import url("URL Imports/Square Everything.css");
@import /url("URL Imports/Select, Input, Textare - Dark Cleaner.css");
/* Extension Themes */
@import url("Misspent Imports/Extension Themes/Feedbro.css");
@import url("Misspent Imports/Extension Themes/Jshelter.css");
@import url("Misspent Imports/Extension Themes/uBlock-Origin.css");
@import url("Misspent Imports/Extension Themes/Auto-Tab-Discard.css");
@import url("Misspent Imports/Extension Themes/Tab-Session-Manager.css");
@import url("Misspent Imports/Extension Themes/Firefox Multi-Containers.css");
```


## 🧩 Extension & Scripts (use/like)
**Extension**:  
- 📌 [uBlock Origin](<https://addons.mozilla.org/en-GB/firefox/addon/ublock-origin/>)
- ⭐ [Stylus](<https://addons.mozilla.org/en-GB/firefox/addon/styl-us/>)
- ⭐ [Violentmonkey](<https://addons.mozilla.org/en-GB/firefox/addon/violentmonkey/>)
- [JShelter](<https://addons.mozilla.org/en-GB/firefox/addon/javascript-restrictor/>)
- [Gesturefy](<https://addons.mozilla.org/en-GB/firefox/addon/gesturefy/>)
- [Vimium C](<https://addons.mozilla.org/en-GB/firefox/addon/vimium-c/>)
- [BlockTube](<https://addons.mozilla.org/en-GB/firefox/addon/blocktube/>)
- [UltimaDark](<https://addons.mozilla.org/en-GB/firefox/addon/ultimadark/>)
- [Chameleon](<https://addons.mozilla.org/en-GB/firefox/addon/chameleon-ext/>)
- [Proton Pass](<https://addons.mozilla.org/en-GB/firefox/addon/proton-pass/>)
- [CanvasBlocker](<https://addons.mozilla.org/en-GB/firefox/addon/canvasblocker/>)  
- [Auto Highlight](<https://addons.mozilla.org/en-GB/firefox/addon/auto_highlight/>)
- [FMHY SafeGuard](<https://addons.mozilla.org/en-GB/firefox/addon/fmhy-safeguard/>)
- [Augmented Steam](<https://addons.mozilla.org/en-GB/firefox/addon/augmented-steam/>)
- [Tab Session Manager](<https://addons.mozilla.org/en-GB/firefox/addon/tab-session-manager/>)
- [Better Volume Booster](<https://addons.mozilla.org/en-GB/firefox/addon/better-volume-booster/>)
- [Firefox Multi-Account Containers](<https://addons.mozilla.org/en-GB/firefox/addon/multi-account-containers/>)
- [uBlacklist](<https://addons.mozilla.org/en-GB/firefox/addon/ublacklist/>)
- - [Awesome uBlacklist](<https://github.com/rjaus/awesome-ublacklist>)
- [Skip Redirect](<https://addons.mozilla.org/en-GB/firefox/addon/skip-redirect/>)
- - [Skip Redirect Lists](<https://gist.github.com/wesinator/a1d7aeed25a17d01ccec91e1188de6fd>)

**Script (ViolentMonkey)**:
- [Pagetual](<https://greasyfork.org/en/scripts/438684-pagetual>)
- [AdsBypasser](<https://adsbypasser.github.io/>)
- [AdGuardExtra](<https://github.com/AdguardTeam/AdGuardExtra>)
- [SearchJumper](<https://greasyfork.org/en/scripts/445274-searchjumper>)
- [Linkify Plus Plus](<https://greasyfork.org/en/scripts/4255-linkify-plus-plus>)
- [IMDb Scout Mod](<https://greasyfork.org/en/scripts/407284-imdb-scout-mod>)
- [Simple Sponsor Skipper](<https://greasyfork.org/en/scripts/453320-simple-sponsor-skipper>)
- [YouTube JS Engine Tamer](<https://greasyfork.org/en/scripts/473972-youtube-js-engine-tamer/post-install>)
- [Double-click Image Downloader](<https://greasyfork.org/en/scripts/469594-double-click-image-downloader>)
- **GitHub**:  [📖 Awesome Userscripts](<https://github.com/awesome-scripts/awesome-userscripts>)



## 📸 Previews (High probability of changing)


### Window Buttons

![Hidden unless hovered](https://github.com/misspent/Firefox-Blackout/blob/main/Images/Window%20Buttons.gif)
- Buttons will be hidden unless hovering over top-right corner

### Compact Discard + Colored coded tabs

![Lovely Tabs](https://github.com/misspent/Firefox-Blackout/blob/main/Images/Compact%20%26%20Discard%20%2B%20Colored%20Tabs.png)

### Extreme compact

![Extreme compact](https://github.com/misspent/Firefox-Blackout/blob/main/Images/Extreme%20Compact.gif)
- Everything but selected is collapsed unless hovered (Width of hovered tab is smaller too) | Has a v2 in the `Extreme Compact Tabs.css` but you'll need to tweak about:config for instant tooltips

### One-Liner

![One-Liner - Without bookmarks](https://github.com/misspent/Firefox-Blackout/blob/main/Images/One-Liner.png)

### Setting & Addons

**Settings**:

![Settings About Page](https://github.com/misspent/Firefox-Blackout/blob/main/Images/Settings%20Page.png)

**Addons**:

![Addons About Page](https://github.com/misspent/Firefox-Blackout/blob/main/Images/Addons%20Page.png)

### New-Tab Page

![New-Tab page (shrunk)](https://github.com/misspent/Firefox-Blackout/blob/main/Images/New-Tab%20page%20(shrunk).jpg)
- You can add your own wallpaper and alter the one in the `New Tab.css`; the variable will probably be transferred to one of the `user` files. Additionally, I know that they now support this natively.



---



<details>
  <summary align="center">📱 Old - Maybe read?</summary>
  <br>

## ⚙️ Installation

1. Download: [LibreWolf](https://librewolf.net) I'm on: `v123.0-1` (about:support)
2. Insert more... Idk what Ima do yet
3. Download: My user.js
4. Open your root directory folder here: `about:profiles`

Check my user.js and remove what you do not want or like. If it's not documented, then I'll add documentation eventually (hopefully).  


- Go to `about:debugging` -> LibreWolf/Firefox/Whatever it's in the sidebar -> Copy the `Internal UUID` hash -> Paste it in the associated Extension support .txt(s) at the top where it looks like a url/import.


### 📃 User JS


**Hardening FireFox**:  
[Betterfox](https://github.com/yokoffing/Betterfox) - Personal recommendation  
[brainfucksec](https://gist.github.com/brainfucksec/68e79da1c965aeaa4782914afd8f7fa2) - Rather detailed  
[Aminomancer](https://github.com/aminomancer/uc.css.js/blob/master/prefs/recommended.js)  
[pyllyukko](https://github.com/pyllyukko/user.js)  
[Arkenfox](https://github.com/arkenfox/user.js)  

Decent videos on it: [1](https://youtu.be/Fr8UFJzpNls) & [2](https://youtu.be/N8IOJiOFVEk)


### 🔎 Extensions Information

**Extension Information**:

LocalCDN: [1](https://www.reddit.com/r/firefox/comments/yd340m/do_you_need_a_cookie_manager_how_about_localcdn/its4xjv)  
ClearURL's: [1](https://www.reddit.com/r/uBlockOrigin/comments/rttrbp/no_longer_any_need_for_the_clearurl_extension/hqxddko) & [2](https://www.reddit.com/r/uBlockOrigin/comments/15smrxu/ublock_origin_is_the_only_extension_you_will_ever/jx64cvt)  
Canvas Blocker: [1](https://discuss.privacyguides.net/t/canvasblocker-firefox-extension/12298) & [2](https://www.reddit.com/r/firefox/comments/7tkw34/how_to_permanently_block_canvas_fingerprinting/dtdi7aq)  


<details>
  <summary align="center">🍻 uBlock Origin filters + Imports</summary>
  <br>

All the Filter lists I have enabled in uBlock Origin: ![Enabled uBlock Origin Filters](https://github.com/user-attachments/assets/d77a2254-d01f-49ac-8ee7-9a918ed9278a)



Links to custom filters from image above:  
[yokoffing's](https://github.com/yokoffing/filterlists#privacy)  
[AdguardFilters](https://github.com/AdguardTeam/AdGuardFilters)  
[Anudeep's Blacklist & Anudeep's Facebook Blacklist](https://github.com/anudeepND/blacklist)  
[Bypass Paywalls Clean filters](https://gitlab.com/magnolia1234/bypass-paywalls-clean-filters)  
[ClearURLs for uBo (unofficial)](https://github.com/DandelionSprout/adfilt/discussions/163)  
[Fanboy's Annoyance List](https://easylist.to)  
[HaGeZi's Personal DNS Blocklist](https://github.com/hagezi/dns-blocklists)  
[1Hosts (Lite)](https://github.com/badmojr/1Hosts)  
[uBlock-Origin-dev-filter – All Search Engines – Global](https://github.com/quenhus/uBlock-Origin-dev-filter)  
[More custom filter lists, found this not long ago, so I thought I'd share.](https://github.com/Universalizer/Universal-FilterLists#privacy)

</details>

<details>
  <summary align="center">🔌 Firefox extension I like/use</summary>
  <br>

| Extension                                                                                               | Optional                                                                                            |
|---------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| [Stylus](https://addons.mozilla.org/en-GB/firefox/addon/styl-us)                                        | [ClearURLs](https://addons.mozilla.org/en-GB/firefox/addon/clearurls)                               |
| [Vimium C](https://addons.mozilla.org/en-GB/firefox/addon/vimium-c)                                     | [Snap Links Plus](https://addons.mozilla.org/en-GB/firefox/addon/snaplinksplus)                     |
| [BlockTube](https://addons.mozilla.org/en-GB/firefox/addon/blocktube)                                   | [Copy All Tab Urls](https://addons.mozilla.org/en-GB/firefox/addon/copy-all-tab-urls-we)            |
| [Gesturefy](https://addons.mozilla.org/en-GB/firefox/addon/gesturefy)                                   | [Temporary Containers](https://addons.mozilla.org/en-GB/firefox/addon/temporary-containers)         |
| [Dark Reader](https://addons.mozilla.org/en-GB/firefox/addon/darkreader)                                | [Reddit Comment Collapser](https://addons.mozilla.org/en-GB/firefox/addon/reddit_comment_collapser) |
| [SponsorBlock](https://addons.mozilla.org/en-GB/firefox/addon/sponsorblock)                             |           |
| [Skip Redirect](https://addons.mozilla.org/en-GB/firefox/addon/skip-redirect)                           |           |
| [Violentmonkey](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey)                           |           |
| [Firefox Color](https://addons.mozilla.org/en-GB/firefox/addon/firefox-color)                           |           |
| [Auto Highlight](https://addons.mozilla.org/en-GB/firefox/addon/auto_highlight)                         |           |
| [History Cleaner](https://addons.mozilla.org/en-GB/firefox/addon/history-cleaner)                       |           |
| [Augmented Steam](https://addons.mozilla.org/en-GB/firefox/addon/augmented-steam)                       |           |
| [Auto Tab Discard](https://addons.mozilla.org/en-GB/firefox/addon/auto-tab-discard)                     |           |
| [Joplin Web Clipper](https://addons.mozilla.org/en-GB/firefox/addon/joplin-web-clipper)                 |           |
| [Tab Session Manager](https://addons.mozilla.org/en-GB/firefox/addon/tab-session-manager)               |           |
| [Reddit Enhancement Suite](https://addons.mozilla.org/en-GB/firefox/addon/reddit-enhancement-suite)     |           |
| [Multi-Account Containers](https://addons.mozilla.org/en-GB/firefox/addon/multi-account-containers)     |           |
| [Bitwarden Password Manager](https://addons.mozilla.org/en-GB/firefox/addon/bitwarden-password-manager) |           |
| [Sound icon can pause & play](https://github.com/Godiesc/firefox-gx/tree/main/Extras/Play-Pause)        |           |

</details>


---


### ⚠️ Other | Random Notes

**Settings**: Settings for clearing history: Do not enable `Browsing & download history` (wipes tabs) - Use: [History Cleaner](https://addons.mozilla.org/en-GB/firefox/addon/history-cleaner)  
**Settings**: Settings for clearing history: Enabling `Offline web site data` wipes volume settings, website tweaks, etc. Keep this disabled if you don't want the fuss.  
**about:config**: `privacy.resistFingerprinting` - Set to `false` if you want zoom levels to stick per page? [Fingerprinting information?](https://www.reddit.com/r/firefox/comments/wi9vee/firefox_and_fingerprinting/ijae7ow/)  

**Customization with Overriders + Other great information (VERY well documented)**:  
[Firefox-UI-Fix Options](https://github.com/black7375/Firefox-UI-Fix/wiki/Options)  
[Tab Bar + Other](https://github.com/black7375/Firefox-UI-Fix/wiki/Options#tab-bar) & [Hides tabs/other stuff until hover (Mega compact)](https://github.com/black7375/Firefox-UI-Fix/wiki/Options#toolbar-overlap-mode)  
[Custom CSS tweaks for Firefox](https://github.com/Aris-t2/CustomCSSforFx)  


**Useful Information or tips**:  
[black7375Wiki](https://github.com/black7375/Firefox-UI-Fix/wiki/Tips) & [Firefox Wiki](https://www.reddit.com/r/firefox/wiki/index)  
Cool Configs/Hub of info: [r/Firefox](https://www.reddit.com/r/firefox) & [Show off your config](https://github.com/black7375/Firefox-UI-Fix/wiki/Show-Off-Your-Config)  
user.js overides: [Common Overides](https://github.com/yokoffing/Betterfox/wiki/Common-Overrides) & [Optional Hardening](https://github.com/yokoffing/Betterfox/wiki/Optional-Hardening)  

**Other**:  
[Backup/Export Firefox Multi-Account Container](https://superuser.com/questions/1394256/how-to-transfer-settings-of-extension-multi-account-containers-in-firefox)  
[Add search shortcuts to your settings with ease](https://mycroftproject.com)  
[CanvasBlocker](https://addons.mozilla.org/en-GB/firefox/addon/canvasblocker) - Not needed w/LibreWolf if you have the resistfingerprint in settings enabled?  
[Cookie AutoDelete](https://addons.mozilla.org/en-GB/firefox/addon/cookie-autodelete) - Not really needed as you can press lock icon and "whitelist" with browser  
[Videos, Articles + Other stuff](https://github.com/yokoffing/Betterfox?tab=readme-ov-file#recognition)  

**Lepton Themes/Icon (ignore for now)**:  

- Open the `leptonContent.css` and remove the whole `@-moz-document url-prefix("https://addons.mozilla.org")` section.  


**Not really relevant if you use my user.js**:  
- Go to `about:config`, search `toolkit.legacyUserProfileCustomizations.stylesheets`, and set it to `true`  
- Go to about:profiles, then click open folder next to Root Directory  
- Open your terminal in the previous folder and run the following command: `git clone https://github.com/benman604/userChrome.css.git chrome`  


### 🚦 Support

**Check Version of browser you're using**: Search: `about:support`  




</details>
