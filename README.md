# BetterBlocklist
<b>Better Blocklist</b> is a collection of powerful and customizable DNS Blocklists against Ads, Tracking and privacy harming Services. Updated regularly with support for Pi-Hole, AdGuard(-Home), uBlock Origin and host Files.

Please contribute if you have any Suggestion by <a href="https://github.com/WilliDieEnte/BetterBlocklist/issues">opening an Issue</a>. 

<a href="https://ente.dev/api/blocklist/"><img alt="Maintained" src="https://img.shields.io/badge/Maintained-yes-brightgreen?style=for-the-badge"></a>
<a href="https://willidieente.mit-license.org"><img alt="License" src="https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge"></a>

### Please note that the lists are not hosted on GitHub and therefore no activity is shown in this Repository, although they are getting updated constantly :)

# Details
A collection of Blocklists for various Purposes. In comparison to other Lists which are all or nothing, you can exactly choose what you want to block.
If you find something in a List that you believe is a mistake or breaks functionality, please contact me. The same goes for unblocked Subdomains of blocked root Domains, please let me know, so I can add it properly.
<br>These Blocklists are <b>compatible with all devices</b>, regardless of the OS, <b>speed up Page Loading</b>, let pages look cleaner, <b>remove most Ads</b>, <b>enhance Privacy</b>, <b>lower bandwidth, CPU, memory and battery usage</b>.

# Usage
<h4>with <a href="https://discourse.pi-hole.net/t/how-do-i-add-additional-block-lists-to-pi-hole/259">Pi-Hole</a>, works almost identical with <a href="https://github.com/AdguardTeam/AdGuardHome">AdGuardHome</a></h4>
<h4>with <a href="https://github.com/gorhill/uBlock/wiki/Filter-lists-from-around-the-web">uBlock Origin</a> (same goes for AdGuard and any similar Add-ons)</h4>
<h4>On Android I recommend using <a href="https://f-droid.org/en/packages/org.adaway/">AdAway</a> and on iOS <a href="https://apps.apple.com/us/app/blokada/id1508341781">Blokada</a></h4>
All lists are accessible using the following Scheme: 
 <br>- Domains only: https://ente.dev/api/blocklist/blocklist-name/
 <br>- Host Files: https://ente.dev/api/blocklist/blocklist-name-hosts/
 <br>Example: https://ente.dev/api/blocklist/suspicious or https://ente.dev/api/blocklist/tracking-hosts

<br>If you need further help, don't hesitate to contact me!

# Lists
| List | Description | Link |
|--| -- |--|
| Advertising | Advertisement Servers / Sites | <a href="https://ente.dev/api/blocklist/advertising">domains</a>, <a href="https://ente.dev/api/blocklist/advertising-hosts">hosts</a> |
| Google-AMP | Blocks <a href="https://www.theregister.com/2017/05/19/open_source_insider_google_amp_bad_bad_bad/">Google AMP</a> Pages | <a href="https://ente.dev/api/blocklist/google-amp">domains</a>, <a href="https://ente.dev/api/blocklist/google-amp-hosts">hosts</a> |
| Suspicious | Includes Fraud, Scams, Malware, Phishing, etc. | <a href="https://ente.dev/api/blocklist/suspicious">domains</a>, <a href="https://ente.dev/api/blocklist/suspicious-hosts">hosts</a> |
| Tracking | Sites and Serviced dedicated to gather info about you | <a href="https://ente.dev/api/blocklist/tracking">domains</a>, <a href="https://ente.dev/api/blocklist/tracking-hosts">hosts</a> |
| TV | Smart TV & Fire TV Telemetery and Ads | <a href="https://ente.dev/api/blocklist/tv">domains</a>, <a href="https://ente.dev/api/blocklist/tv-hosts">hosts</a> |
| TikTok | Blocks TikTok, formerly known as Musically | <a href="https://ente.dev/api/blocklist/tiktok">domains</a>, <a href="https://ente.dev/api/blocklist/tiktok-hosts">hosts</a> |
| YouTube-ADS | Blocks most Ads without blocking actual YouTube Videos | <a href="https://ente.dev/api/blocklist/youtube-advertising">domains</a>, <a href="https://ente.dev/api/blocklist/youtube-advertising-hosts">hosts</a> |

# Experimental Lists
| List | Description | Link |
|--| -- |--|
| Amazon | Tries to block Amazon, without blocking AWS | <a href="https://ente.dev/api/blocklist/amazon">domains</a>, <a href="https://ente.dev/api/blocklist/amazon-hosts">hosts</a> |
| Apple | An Apple a Day keeps your Money away! | <a href="https://ente.dev/api/blocklist/apple">domains</a>, <a href="https://ente.dev/api/blocklist/apple-hosts">hosts</a> |
| Cloudflare | Blocks the Cloudflare Network | <a href="https://ente.dev/api/blocklist/cloudflare">domains</a>, <a href="https://ente.dev/api/blocklist/cloudflare-hosts">hosts</a> |
| Crypto | Blocks Crypto Sites and prevents mining | <a href="https://ente.dev/api/blocklist/crypto">domains</a>, <a href="https://ente.dev/api/blocklist/crypto-hosts">hosts</a> |
| Facebook | Block all Services relating to Facebook, Instagram & WhatsApp | <a href="https://ente.dev/api/blocklist/facebook">domains</a>, <a href="https://ente.dev/api/blocklist/facebook-hosts">hosts</a> |
| Google | Blocks Google Services, including YouTube | <a href="https://ente.dev/api/blocklist/google">domains</a>, <a href="https://ente.dev/api/blocklist/google-hosts">hosts</a> |
| Microsoft | Attempts to block all Microsoft Services, including Skype | <a href="https://ente.dev/api/blocklist/microsoft">domains</a>, <a href="https://ente.dev/api/blocklist/microsoft-hosts">hosts</a> |
| Pinterest | Blocks Pinterest | <a href="https://ente.dev/api/blocklist/pinterest">domains</a>, <a href="https://ente.dev/api/blocklist/pinterest-hosts">hosts</a> |
| Snapchat | Blocks the usage of Snapchat | <a href="https://ente.dev/api/blocklist/snapchat">domains</a>, <a href="https://ente.dev/api/blocklist/snapchat-hosts">hosts</a> |
| Twitter | Blocks <strike>the trash Fire</strike> <strike>Twitter</strike> X? | <a href="https://ente.dev/api/blocklist/twitter">domains</a>, <a href="https://ente.dev/api/blocklist/twitter-hosts">hosts</a> |

Please open an Issue if you find any false flag or have any Domain that should be added to any Blocklist.

# Awesome Projects
Thanks to the following, great Projects that are partially included in BetterBlocklist adding to my own Research (and maybe even yours, I would appreciate your Contribution :)
- https://blocklist-tools.developerdan.com/blocklists
- https://prism-break.org/
- https://github.com/gorhill/uBlock
- https://adblockplus.org/
- https://privacyguides.org/
- https://adguard.com/
- https://adaway.org/
- https://disconnect.me/
- https://firebog.net/
- https://hmirror.molinero.dev/
- https://coveryourtracks.eff.org/

# Additions
- Dependencies are updated automatically every day.


- <a href="https://www.makeuseof.com/tag/stop-using-ccleaner-windows/"><b>Why should I avoid CCleaner?</b></a>

- Your hosts file Location:
   - Linux, Unix and Mac OS X -> ``/etc/hosts``
   - Windows XP, Vista, 7, 8, 10 and 11 -> ``C:\WINDOWS\system32\drivers\etc\hosts``
   - Windows 2000 -> ``C:\WINNT\system32\drivers\etc\hosts``
   - Windows 98/ME -> ``C:\WINDOWS\hosts``
<br><b>WARNING: Do not use Host files larger than 1MB on Windows directly, Windows can't handle that and won't do any lookups anymore for some obscure reason. Rather use <a href="https://pi-hole.net/">Pi-Hole</a> or <a href="https://github.com/AdguardTeam/AdGuardHome">AdGuardHome</a></b>

- The ente.dev Domain uses Cloudflare <a href="https://www.cloudflare.com/products/argo-smart-röouting/">Argo Smart Routing</a> and <a href="https://www.cloudflare.com/cdn/">CDN</a> in combination with a strong Server for the fastest delivery possible globally, so you shouldn't experience much delay in pulling updates from these lists.

- <a href="https://docs.pi-hole.net/guides/dns/unbound/#setting-up-pi-hole-as-a-recursive-dns-server-solution"><b>I very much recommend you to use unbound in addition to Pi-Hole for better Privacy</b></a>

A great Way of finding fake Shops is just searching the following Keywords:
 - <a href="https://duckduckgo.com/?q=Kindly+keep+in+mind+that+we+produce+on+demand.+We+do+not+stock+items">Kindly keep in mind that we produce on demand. We do not stock items</a>
 - <a href="https://duckduckgo.com/?q=Every+day+we+receive+more+appreciative+emails+from+satisfied+customers+all+over+the+world">Every day we receive more appreciative emails from satisfied customers all over the world</a>
 - <a href="https://duckduckgo.com/?q=Everyday%2C+we+strive+to+deliver+high+quality+products+with+the+greatest+customer+experience+possible">Everyday, we strive to deliver high quality products with the greatest customer experience possible</a>

If you have any questions about this project, open an issue and let's have a discussion! :3

# Disclaimer
The lists contained here are provided as is, with no warranty as to their accuracy. It is your responsibility to whitelist/blacklist as you see fit for your needs and your environment. These lists are provided free of charge, are open for use by anyone, and are maintained by myself in my spare time. These lists are collections of domains I have come across, therefore these are not perfectly curated and vetted lists, however I try to do my best to avoid false positives and inaccuracies in all cases.
