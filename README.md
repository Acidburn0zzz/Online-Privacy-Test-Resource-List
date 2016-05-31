# - POTARC -

Privacy Online Test And Resource Compendium© project original created under the MIT license 2016 by CHEF-KOCH and community.

# Privacy Online Test And Resource Compendium

This list is designed to show all available (and useful) online tests, we may not add each test if it's unclear if it collects only data to hand/sell it to 3th-party developer or people which pay for it to use it for 'bad' things. 

I see this as a 'community' based project since everyone can contribute and no one ever will excluded (only with good reasons like spamming, ...). I/we not accept any donations because we all doing this in our free time and it's up to everyone. The information should be avaible for free for everyone. 


**ToDo:**
* Add github-gh page (front-page)
* Add (maybe) gitter chat 
* Add an page index to easier navigate to the specific sections 
* Table view?
* Add small overview what the page exactly do
* Add a warning that all of these pages mostly require JavaScript which must be e.g allowed via NoScript/umatrix.
* Some pages itself may collecting a online/offline database?! Research + proof needed. But it would make sense if they sell the collected data to Google, Amazon and others ... 
* Mark deprecated (because fixed by OS/Browser) test with an icon? It would help to identify if that is already fixed or not to avoid to submit unessary data and of course it would costs your time ... 


**Known Fingerprinting Techniques:**
* Mouse Speed fingerprinting
* CPU Benchmark fingerprinting
* User fingerprinting problem (Canvas, IP, ...)
* Screen resolution (this possible will never be fixed since it would break too much)
* UberCookie/Cookies/EverCookie/Supercookies
* Measuring time (Timezone/[NTP](http://www.securityweek.com/ntp-servers-exposed-long-distance-wireless-attacks))
* getClientRects fingerprinting (DOM)
* OSI model fingerprints (HTTP, Header, User Agent, Firewall, ...)
* Hardware implemented fingerprint methods 
* Plugin/Extension tracking (Silverlight, Adobe Flash, ...)
* Tor detection
* DNS leakage or bypasses
* Stuff which is documented and mentioned over [here](https://github.com/CHEF-KOCH/NSABlocklist).
* ....


**Fixed within the Browser (ensure you using the latest product [always])**
* SSL / TLS (ciphers) [if you only browsing on pages like GitHub ~ you can even more '[harden](https://tools.ietf.org/html/draft-sheffer-tls-bcp-00)' it]
* OpenSSL fixed (heartbleed,...) 
* Chrome: Audio Fingerprinting not possible Firefox: **not tested (yet) - need feedback!**
* Tor (several fingerprints still possible, it's on the todo and will be fixed soon)
* Java/Adobe Flash, both are dying -> HTML5 -> canvas
* HTML5 several stuff like Canvas, Font, ... (will never be fixed, use addons)
* Cookies in general are not fixable since your page may need it, Amazon for shopping as an example (addons/filter-lists may help to whitelist).
* CPU, mouswheel fingerprinting which needs to be fixed also within the OS (still open)
* MAC address leakage - disable IPv6 (if not nessary/needed)
* WebRTC (partial) since Chrome 48 and Firefox 42, both getting an new menu to allow it per-page (whitelist) [there exist also for both several addons, workarounds to compile it without WebRTC support)
* PopUps are (if not Canvas/JS related) not anymore possible, you see a permission Dialog or can control this behavior directly via Browser settings
* .... 

**How to handle this?**

Collection of device fingerprints from web clients (browser software) relies on the availability of JavaScript or similar client-side scripting language for the harvesting of a suitably large number of parameters. Overall this means if only one or a small of things are detectable it not automatically reveals your true identify, but all together is pretty dangerous.


### Addon & Plugin Tests

Firefox Addon Detector:
https://thehackerblog.com/addon_scanner/

Flash Player System Test:
https://www.browserleaks.com/flash

Flash Player Test:
https://www.adobe.com/software/flash/about/

Java Test:
https://www.java.com/en/download/installed.jsp

Silverlight Test:
https://www.browserleaks.com/silverlight


### eMail

Check Provider-TLS:
https://www.checktls.com/

Email IP Leak Test:
http://emailipleak.com/

Email Privacy Tester:
https://emailprivacytester.com/

Email Trace:
http://www.ip-adress.com/trace_email/

Have I Been Pwned?:
https://haveibeenpwned.com/

Pwnedlist:
https://pwnedlist.com/


### HTML5 test

Battery Status API:
http://pstadler.sh/battery.js/

Canvas Fingerprinting:
https://www.browserleaks.com/canvas

Hard Drive Fill Test:
http://www.filldisk.com/

HTML5 Features Detection:
https://www.browserleaks.com/modernizr

HTML5 Geolocation Test:
https://www.browserleaks.com/geo

HTML5 Test:
http://html5test.com/

WebRTC Leak Test:
https://www.perfect-privacy.com/webrtc-leaktest/

WebRTC Test:
https://test.webrtc.org/

WebRTC What's My IP Check:
http://whatismyipaddress.com/webrtc-test


### IP & DNS Leak Tests

Check My Torrent IP:
https://torguard.net/checkmytorrentipaddress.php

Content Filters and Proxy Test:
https://www.browserleaks.com/proxy

DNS Leak Test:
https://www.dnsleaktest.com/

DNS Spoofability Test:
https://www.grc.com/dns/dns.htm

IPv4/IPv6 Discovery / Detection Test:
https://www.perfect-privacy.com/check-ip/

IP Magnet Test:
http://ipmagnet.services.cbcdn.com/

Whois Test (Windows):
https://www.browserleaks.com/whois


### Privacy Management

Google Account History:
https://www.google.com/settings/accounthistory

Facebook Activity Log:
https://www.facebook.com/me/allactivity

YouTube Video History / Search History:
https://www.youtube.com/feed/history


### SSL Test

Bad SSL:
https://badssl.com/

FREAK Attack: Client Check:
https://freakattack.com/clienttest.html

Heartbleed Test:
https://filippo.io/Heartbleed/

RC4 Fallback Test:
https://rc4.io/

How's My SSL:
https://www.howsmyssl.com/

SSL Cipher Suite Details:
https://cc.dcsec.uni-hannover.de/

Weak Diffie-Hellman and the Logjam Attack:
https://weakdh.org/


### Random Tests (DNT, Evercookie, Headers, Javascript,...)

BrowserRecon (Header/HTTP) Test:
http://www.computec.ch/projekte/browserrecon/?s=scan

What Is My Referer?:
https://www.whatismyreferer.com/

Browser Referer Headers:
https://www.darklaunch.com/tools/test-referer

Do Not Track Test:
https://www.browserleaks.com/donottrack 

Evercookie Test:
http://samy.pl/evercookie/

JavaScript Browser Information:
https://www.browserleaks.com/javascript

Popup Blocking Tests:
http://www.kephyr.com/popupkillertest/index.html

Redirect Page Test:
https://jigsaw.w3.org/HTTP/300/Overview.html

System Fonts Detection Test:
https://www.browserleaks.com/fonts

JavaScript/CSS Font Detector:
http://www.lalit.org/lab/javascript-css-font-detect/

Universal Plug n'Play (UPnP) Internet Exposure Test:
https://www.grc.com/x/ne.dll?rh1dkyd2

JavaScript: PasteJacking:
https://www.sempervideo.de/pastejacking/


### Advanced Tests

Am I Unique?:
https://amiunique.org/fp

Browser Spy (Multiple Tests):
http://browserspy.dk/

Cross Browser Fingerprinting Test:
http://fingerprint.pet-portal.eu/#

IP Leak:
https://ipleak.net/

Jondonym Full Anonymity Test:
http://ip-check.info/?lang=en

Panopticlick:
https://panopticlick.eff.org/

PC Flank:
http://www.pcflank.com/index.htm

Onion Leak Test:
http://cure53.de/leak/onion.php

Tor Fingerprint Test:
https://tor.triop.se/

Whoer:
https://whoer.net/

Popup Test:
http://www.popuptest.com/

Privacy Check:
http://do-know.com/privacy-test.html

Audio Fingerprint Test (see also [here](https://github.com/Gitoffthelawn)):
https://audiofingerprint.openwpm.com/

Browser 'auto-download' Security Vulnerability (Chrome, IDM affected at time of writing):
https://binaer.xyz/haifei-li/test.html
