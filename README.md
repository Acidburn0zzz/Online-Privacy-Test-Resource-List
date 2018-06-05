 ## - POTARC -

Privacy Online Test And Resource Compendium© (short: POTARC) project original created under the MIT license 2016 - 2018 by CHEF-KOCH and community.

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40CHEF-KOCH)](https://twitter.com/CKsTechNews)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/CHEF-KOCH)
[![Discord](https://discordapp.com/api/guilds/418256415874875402/widget.png)](https://discord.me/CHEF-KOCH)

## Privacy Online Test And Resource Compendium

The list is designed to show all available and useful online/offline tests in order to build strategies to harden your OS/Internet/Browser configuration against fingerprinting methods. Some of those services might collect only data to hand/sell it to 3th-party developer or people which pay for it to use it for 'bad' things, such services are (if known) marked and aren't preferable added - so keep this in mind before you request a site. 

POTARC itself is more a community driven project because everyone can contribute to it and no pull request or discussion will be rejected, only with good reasons like spamming, etc. . This project does not accept any donations because we all doing this in our free time and it's up to everyone. The information should be available for free for everyone.

## Contribution

See [CONTRIBUTING.md](https://github.com/CHEF-KOCH/Online-Privacy-Test-Resource-List/blob/master/CONTRIBUTING.md). Before you create a new issue ticket, ensure you read the issue template and check if the things you like to request is not already on the todo list in order to avoid duplicates or already known things. 


## How to handle the information and test results?

Collection of [device fingerprints](https://en.wikipedia.org/wiki/Device_fingerprint) from web clients  such as browser software mostly relies on the availability of JavaScript or similar client-side scripting language for the harvesting of a suitably large number of parameters. Overall this means if only one or a small of things are detectable it not automatically reveals your real identify, but all together can be pretty dangerous in order to expose you or your security setup. Keep in mind that it's not a good idea to share the results or to leak information which setup you exactly use.

The document section is for research and evidence purposes, topics without any proof are not reliable and the project doesn't accept any submissions without any documents or research based on the matter.

Keep in mind
> Some of the integrated services & pages collect the results and store it offline and some even sell the results to 3rd-parties! I'm not responsible for this behavior, the list will add an indicator for services which doing it soon.


### Known Fingerprinting Techniques
* [Audio fingerprint tests](https://github.com/worldveil/dejavu), [example](https://github.com/dpwe/audfprint).
* [OSI model fingerprints](https://searchnetworking.techtarget.com/tip/OSI-Securing-the-Stack-Layer-4-Fingerprinting) (based on [HTTP](https://github.com/wireghoul/lbmap), Header, User Agent, Firewall, ...)
* [CPU Fingerprint](http://yinzhicao.org/TrackingFree/crossbrowsertracking_NDSS17.pdf)
* [Mouse & CPU fingerprinting](http://jcarlosnorte.com/security/2016/03/06/advanced-tor-browser-fingerprinting.html)
* [User fingerprinting problem (Canvas, IP, ...)](https://en.wikipedia.org/wiki/Canvas_fingerprinting)
* [Screen resolution](http://www.b3rn3d.com/blog/2014/05/29/fingerprinting-resolution/)
* [UberCookie](http://ubercookie.robinlinus.com/faq.html)/[Cookies](https://en.wikipedia.org/wiki/HTTP_cookie)/[EverCookie](https://en.wikipedia.org/wiki/Evercookie)/[Supercookies](https://en.wikipedia.org/wiki/HTTP_cookie#Supercookie)
* [Database fingerprints](https://github.com/Valve/fingerprintjs2)
* [Measuring time](https://en.wikipedia.org/wiki/Timing_attack) (Timezone/[NTP](http://www.securityweek.com/ntp-servers-exposed-long-distance-wireless-attacks))
* getClientRects fingerprinting via [DOM](http://www.water.ca.gov/waterquality/docs/Fingerprinting%20Sources%20of%20DOM%20-%20Ngatia.pdf)
* Hardware implemented fingerprint methods such as [hardware based DRM](https://docs.microsoft.com/en-us/windows/uwp/audio-video-camera/hardware-drm)
* [Plugin/Extension tracking](https://webdevwonders.com/detecting-browser-plugins/) (Silverlight, Adobe Flash, ...)
* [Tor node detection](https://check.torproject.org/)
* [DNS leakage or bypasses](https://www.dnsleaktest.com/what-is-a-dns-leak.html)
* [Cross-Origin Identifier](https://www.torproject.org/projects/torbrowser/design/#identifier-linkability)
* [Do not track (DNT) detection](https://econsultancy.com/blog/6921-the-ftc-s-do-not-track-proposal-useless-harmful-or-both)
* [Font detection & vulnerabilities](https://support.microsoft.com/en-us/kb/2639658)
* [Caching attacks](https://en.wikipedia.org/wiki/Timing_attack)
* [PushAPI](https://developer.mozilla.org/en-US/docs/Web/API/Push_API)
* [ServiceWorker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/)
* [TLS](https://github.com/LeeBrotherston/tls-fingerprinting)
* [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
* [Battery API](https://www.w3.org/TR/battery-status/)
* [AJAX](http://www.symantec.com/connect/articles/ajax-security-basics)
* [CORS (ajax)](http://www.html5rocks.com/en/tutorials/cors/)
* [WebSocket](http://resources.infosecinstitute.com/websocket-security-issues/)
* [Password sniffing](http://cng.seas.rochester.edu/CNG/docs/Security/node8.html)
* [Canvas](http://cseweb.ucsd.edu/~hovav/dist/canvas.pdf)
* Several [HTTP authorization detection](https://en.wikipedia.org/wiki/Security_testing#Authentication) which is not fixable because it's protocol and meta-data depending and would require new metadata less protocols.
* [CPU Starvation Attacks](https://msdn.microsoft.com/en-us/library/ee810608(v=cs.20).aspx)
* [Memory Starvation Attacks](https://msdn.microsoft.com/en-us/library/ee810601(v=cs.20).aspx)
* [Resource Starvation Attacks](https://msdn.microsoft.com/en-us/library/ee798408(v=cs.20).aspx)
* [Network Bandwidth Attacks](https://msdn.microsoft.com/en-us/library/ee798452(v=cs.20).aspx)
* [ISP throttling checks](https://thenextweb.com/apps/2015/05/21/quick-test-shows-if-isps-are-secretly-throttling-your-internet-speeds/)
* CDN [Web Cache Deception Attack](https://omergil.blogspot.ch/2017/02/web-cache-deception-attack.html). CDN's are in general a security problem, once infected or compromised you have no chance to identify the threat or not before it's already too late. [Decentraleyes](https://github.com/Synzvato/decentraleyes) reduce the attack surface.
* [Extension system based attacks](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-sanchez-rola.pdf)
* [NoCoin](https://github.com/keraf/NoCoin), prevents background mining via opt-in.
* [Urchin Tracking Module (UTM)](https://support.google.com/urchin/answer/28307?hl=en)
* [uBeacons](https://www.ubuduasia.com/single-post/2015/12/02/Leverage-Data-Analytics-to-reevaluate-your-marketing-effort-using-uBeacons-)
* Fake identity, Identify theft (not fixable) & Fake Comments
* [Crooked Style Sheets](https://www.mike-gualtieri.com/posts/stealing-data-with-css-attack-and-defense) [Discussion](https://news.ycombinator.com/item?id=16157773)
* [User agent detection](https://en.wikipedia.org/wiki/Usage_share_of_web_browsers#User_agent_spoofing)
* [Zero With Detection](https://umpox.github.io/zero-width-detection/)
* [Acoustic fingerprinting](https://en.wikipedia.org/wiki/Acoustic_fingerprint)
* [Automatic content recognition](https://en.wikipedia.org/wiki/Automatic_content_recognition)
* [Canvas fingerprinting](https://en.wikipedia.org/wiki/Canvas_fingerprinting)
* [Digital video fingerprinting](https://en.wikipedia.org/wiki/Digital_video_fingerprinting)
* [Public key fingerprint](https://en.wikipedia.org/wiki/Public_key_fingerprint)
* [Common Spoofing attacks](https://en.wikipedia.org/wiki/Spoofing_attack)
* [Tor Browser Security Design](https://www.torproject.org/projects/torbrowser/design/)
* [ASN Squatting Attacks](http://securityskeptic.typepad.com/the-security-skeptic/2011/06/asn-squatting-attacks.html)
* Power consumption and wave signal based tests (not fixable without breaking the signals!).
* [IDN homograph attack](https://en.wikipedia.org/wiki/IDN_homograph_attack)
* [Clickjacking](https://www.vojtechruzicka.com/preventing-clickjacking/)
* Stuff which is documented and mentioned over [here](https://github.com/CHEF-KOCH/NSABlocklist) or [here](https://wiki.mozilla.org/Fingerprinting)
* [SameSite cookies](https://tools.ietf.org/html/draft-ietf-httpbis-rfc6265bis-02#section-5.3.7)
* [DNS cookies](http://dnscookie.com/)


### Already fixed within the Browser (ensure you using the latest product [always])
* SSL / TLS (ciphers) [if you only browsing on pages like GitHub ~ you can even more '[harden](https://tools.ietf.org/html/draft-sheffer-tls-bcp-00)' it]
* OpenSSL fixed (heartbleed,...) 
* Tor (several fingerprint methods are still possible, it's on the todo and will be fixed soon (?))
* Java/Adobe Flash, both are dead and replaced by HTML5 (which has it's own weaknesses) 
* HTML5 several stuff like Canvas, Font, ... (will never be fixed, you have to use  in order to spoof such data)
* Cookies in general are not fixable since your visited page may need it, Amazon for shopping as an example (addons/filter-lists may help to whitelist). But you can disable the cookie collection and work instead with a whitelist, every Browser does support this.
* CPU & Mouse wheel fingerprinting which needs to be fixed also within the OS (this is a wontfix!) 
* Network layer based leaks like MAC address leakage. Disabling/blocking IPv6, if not necessary/needed is enough. See [RFC 3041](https://tools.ietf.org/html/rfc3041).
* WebRTC since Chrome 48+ and Firefox 42+, both getting an new menu to allow it per-page (whitelist). There exist also for both several addons, workarounds to compile it without WebRTC support). [Unofficial Chromium builds](http://chromium.woolyss.com) also come without WebRTC or sync.
* PopUps aren't possible anymore, if not Canvas/JS related). You see a permission dialog or can control this behavior directly via Browser settings. Some [Browsers also come with their own Ads-blocking feature](https://www.theverge.com/2018/2/14/17011266/google-chrome-ad-blocker-features).
* Browser based download attacks by exposing sensible information. 



## Obsolete Add-ons & Plugin Tests

| **Page or Addon** | **Description** | **Collects or sells user data?** |
| --- | --- | --- |
| [Firefox Addon Detector](https://thehackerblog.com/addon_scanner/) | ://URI detection | `No` |
| [Flash Player System Test](https://www.browserleaks.com/flash) | Checks if and what version or Adobe Flash Player is installed | `No` |
| [Adobe official Flash Player Test](https://www.adobe.com/software/flash/about/) | Official Adobe Flash Player Test | `Yes` collects statistics and sells them. |
| [Java Test](https://www.java.com/en/download/installed.jsp) | Official Java Browser verification page. | `Yes` collects statistics and sells them. |
| [Unofficial Microsoft Silverlight Test](https://www.browserleaks.com/silverlight) | Browserleaks Silverlight Test Page | `No` |



## Add-ons e10s check

| **Page or Addon** | **Description** | **Collects or sells user data?** |
| --- | --- | --- |
| [Firefox Compatible check](https://www.arewee10syet.com/) | Checks if your Firefox Browser is e10s compatible | `N/A` |



## eMail

| **Page or Addon** | **Description** | **Collects or sells user data?** |
| --- | --- | --- |
| [Email IP Leak Test](http://emailipleak.com/) | Checks if your email provider shows your real IP address to its recipients. | `N/A` |
| [Email Privacy Tester](https://emailprivacytester.com/) | Checks email addresses | `Yes` see [here](https://www.emailprivacytester.com/privacy) |
| [Email Trace](http://www.ip-adress.com/trace_email/) | Checks email addresses | `Yes` |
| [Have I Been Pwned?](https://haveibeenpwned.com/) | Database which checks if you affected by several holes | `No` | 
| [Pwnedlist](https://pwnedlist.com/) | Database which checks if you affected by several holes | `Yes` - Currently down |
| [Check Your GPG Fingerprints](https://evil32.com/) | Check if your GPG key is leaked or not | `No` |
| [Have I Been Sold?](https://haveibeensold.app/) | Quickly check if your email has been sold. | `No`, database lookup needs JS



## Phishing
| **Page** | **Description** | **Collects or sells user data?** |
| --- | --- | --- |
| [KnowBe4](https://www.knowbe4.com/phishing-security-test-offer) | Login to get your phishing test template | [Yes](https://www.knowbe4.com/privacy-policy).



## Browser Prerender & feature Tests
| **Page** | **Description** | **Collects or sells user data?** |
| --- | --- | --- |
| [Prerender test](http://prerender-test.appspot.com/) | [Prerender](https://www.keycdn.com/blog/resource-hints/) resource test | `No` |
| [Web platform's features check](http://paulirish.github.io/web-feature-availability/) | Test which Web Feature your Browser supports | Yes, StatCounter & caniuse.com |



## Window Measurements
| **Page or Addon** | **Description** | **Collects or sells user data?** |
| --- | --- | --- |
| [Inner Window Measurements](https://fiprinca.0x90.eu/poc/) | Detects the Browser Window Size | `No` |



## Certificate 

| **Page or Addon** | **Description** | **Collects or sells user data?** |
| --- | --- | --- |
| [Revocation Awareness Test](https://www.grc.com/revocation.htm) | Certificate based revocation test | `No` |
| [Check Provider-TLS](https://www.checktls.com/) | Check provider TLS certificates | `N/A` | 
| [Intermediate CA Cache Fingerprinting](https://fiprinca.0x90.eu/poc/) | Intermediate CA Cache Fingerprinting | `No` |



## Crypto-mining detection and Malware

| **Page or Addon** | **Description** | **Collects or sells user data?** |
| --- | --- | --- |
| [MALWARE DETECTED WITH THREAT EMULATION](http://www.cpcheckme.com/checkme/) | Check if your security setup is ready against crypto mining and other threats | `Yes` |


## HTML5 based features test

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Basic HTMl5 Video and Audio tester](http://tools.woolyss.com/html5-audio-video-tester/) | HTMl5 Video and Audio tester | `No` | `No` |
| [Battery Status API](http://pstadler.sh/battery.js/) | Checks if you browser supports Battery Status API | `No` | `No` |
| [Battery Status API](https://pazguille.github.io/demo-battery-api/) | Another Battery Status API Test | `No` | `Yes` |
| [Canvas Fingerprinting](https://www.browserleaks.com/canvas) | Checks your Canvas Fingerprint | `N/A` | `Yes` |
| [Canvas.toBlob test](https://blueimp.github.io/JavaScript-Canvas-to-Blob/test/) | Checks your Canvas Blob Fingerprint | `N/A` | `Yes` |
| [Canvas Blocking Detection](https://kkapsner.github.io/CanvasBlocker/test/detectionTest.html) | Detects if you block Canvas | `No` | `No` |
| [get.Image Canvas test](http://tutorialspark.com/html5/HTML5_Canvas_get_Image_Data_Demo.php) | Checks your get.Image Fingerprint | `N/A` | `Yes` |
| [HTML5 Features Detection](https://www.browserleaks.com/modernizr) | Detects which HTML5 features your Browser is capatible of | `N/A` | `Yes` |
| [Hard Drive Fill Test](http://www.filldisk.com/) | Hard Drive Fill Test (local Storage) | `Yes` | `Yes` |
| [HTML5 Geolocation Test](https://www.browserleaks.com/geo) | HTML5 based Geolocation Test | `No` | `Yes` |
| [HTML5 Test](http://html5test.com/) | Official HTML5 test landing page | `No` | `Yes` |
| [HTML5 Security Cheatsheet](https://html5sec.org/) | HTML5 Security checklist | `N/A` | `Yes` |
| [WebRTC Leak Test](https://www.perfect-privacy.com/webrtc-leaktest/) | Perfect Privacy WebRTC Leakage Test | `Yes` | `Yes` |
| [WebRTC Leak Test](https://diafygi.github.io/webrtc-ips/) | WebRTC Leak Test | `No` | `Yes` |
| [WebRTC Test](https://test.webrtc.org/) | WebRTC Official test | `N/A` | `Yes` |
| [WebRTC What's My IP Check](http://whatismyipaddress.com/webrtc-test) | WebRTC IP Check | `Yes` | `Yes` |
| [WebRTC check by PrivacyTools.io](https://www.privacytools.io/webrtc.html) | WebRTC IP Check | `No`, [source code is here](https://github.com/diafygi/webrtc-ips). | `No` |
| [Web RTC Chrome vulnerability check](https://internet-israel.com/internet_files/webrtc/index.html) | See ([Bug 709952](https://bugs.chromium.org/p/chromium/issues/detail?id=709952)) | `No` | `No` |
| [Anonymster WebRTC check](https://anonymster.com/web-rtc-leak-test/) | Another WebRTC check | `No` | `Yes` |



## CSS Fingerprint Test

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Crooked Style Sheets](http://crookedss.bplaced.net/) | Crooked Style Sheets fingerprinting test page | `No` | `Yes` ([Source Code](https://github.com/jbtronics/CrookedStyleSheets))|



## IP, DNS & Magnet Leak Tests

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [GeoTek Datentechnik - Web Privacy Check](https://ipinfo.info/html/privacy-check.php) | Basic Web Privacy Check | `No` | `Yes` |
| [DoiLeak](https://www.doileak.com/) | Checks if you real IP is leaking behind Proxy/VPN | `N/A` | `Yes` |
| [IP Leak](https://ipleak.net/) | Most well-known IP leak check | `Yes` | `Yes` |
| [DNS Leak Test](https://www.dnsleaktest.com/) | Most well-known DNS leak check | `Yes` | `Yes` |
| [Content Filters and Proxy Test](https://www.browserleaks.com/proxy) | Check your filter list and Proxy configuration | `N/A` | `Yes` |
| [DNS Spoofability Test](https://www.grc.com/dns/dns.htm) | Is your DNS spoofed? | `Yes` | `Yes` |
| [IPv4/IPv6 Discovery / Detection Test](https://www.perfect-privacy.com/check-ip/) | Checks your current IPv4/IPv6 configuration | `N/A` | `Yes` |
| [Whois Test](https://www.browserleaks.com/whois) | Basic Whois Test for Windows Users | `No` | `Yes` |
| [Mirai Vulnerability Scanner](https://www.incapsula.com/mirai-scanner/) | Basic Network Vulnerability Scanner | `N/A` | `Yes` |
| [Galhi US Test](http://ip.galih.us) | Simple IP check | `No` | `No` |
| [Check your current IP](http://checkip.dyn.com) | Yet another IP checker alternative | `N/A` | `No` |
| [ipx.ac](https://ipx.ac/run) | Offers IPv6, Geo, DNS, WebRTC FlashIP, Battery, user-Agent and more tests | `No` | `No` |



## Privacy Management

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Google Account History](https://www.google.com/settings/accounthistory) | View, manage or delete your Google Account History | `N/A` | `No` |
| [Facebook Activity Log](https://www.facebook.com/me/allactivity) | View, manage or delete your Facebook Account History | `N/A` | `No` |
| [YouTube Video History / Search History](https://www.youtube.com/feed/history) | Check your YouTube Account Feed History | `N/A` | `Yes` |
| [Microsoft Account Credentials Leak vulnerability check](https://msleak.perfect-privacy.com/) | Microsoft Account Credentials Leak vulnerability check | `Yes` Collects and stores the results | `Yes` |
| [Webbkoll](https://github.com/andersju/webbkoll) | Checks website reputation and additional security related infos | `No` | `No` |
| [Browser Extension and Login-Leak Experiment](https://extensions.inrialpes.fr/) | Browser Web Beacon test | `Yes` see [here](https://extensions.inrialpes.fr/privacy.php) | `No` |
| [Hide my Footprint](https://hmfp.absolutedouble.co.uk/) | Checks your Browser footprint | `Yes` | `Yes` |
| [Browsers leak installed extensions PoC](https://github.com/earthlng/testpages) | Detect installed Extensions | `No` | `No` |
| [Information Disclosure on IE](https://www.cracking.com.ar/demos/ieaddressbarguess/) |  Check if Internet Explorer leaks sensible Information |`Yes` | `No` |
| [ETag](http://lucb1e.com/rp/cookielesscookies/) | ETAG (Cookieless Cookies) Test | `Yes` stores results in an offline database | `Yes` |
| [Overview of all supported Two-Factor Auth (2FA) pages](https://twofactorauth.org/) | Lists all 2FA supported pages | `N/A` | `No` |
| [ASN Blocklist](https://www.enjen.net/asn-blocklist/) | Lists and shows ASN Providers | `N/A` | `No` |
| [Nextcloud Security Scan](https://scan.nextcloud.com) | Nextcloud Security Scan | `Yes` | `Yes` |
| [Test your IPv6 connectivity](https://test-ipv6.com/) | Open Source IPv6 test | [No](https://test-ipv6.com/faq.html.en_US) | `No` |
| [IP Duh](http://ipduh.com/anonymity-check/) | eTag, Ip and other checks | `Yes` | `N/A` | 
| [Zscaler](http://securitypreview.zscaler.com/) | Security Check | `Yes` | `Yes` |
| [GRC](https://www.grc.com/fingerprints.htm) | GRC Fingerprints check | `N/A` | `No` |
| [CSS Keylogger with no CSP](https://no-csp-css-keylogger.badsite.io) | This site has no Content Security Policy to protect against CSS injections, and demonstrates a keylogger using only injected CSS with React as the controlled JavaScript framework. | `N/A` | `No` | 
| [HTTP Request & Response Service](https://httpbin.org/) | Check eTAg | `N/A` | `No` | 
| [Browser Audit](https://browseraudit.com/) | Several browser tests | `N/A` | `Yes` | 
| [FP Central](https://fpcentral.irisa.fr/) | Statistics to Fingerprints (global), Tor, JavaScript tests etc | `No`, it's [open source](https://github.com/plaperdr/fp-central). | `Yes` | 
| [PoC for cookieless tracking via cache](http://cookieless-user-tracking.herokuapp.com/) |  It can't be defeated except by periodically clearing your Browser cache. [Original Article](https://robertheaton.com/2014/01/20/cookieless-user-tracking-for-douchebags/) | `No` | `No`, [source code](https://github.com/robert/cookieless-user-tracking). |



## Resource:// URIs leak checks 

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Arthured Elstein resource:// URIs leak information page](https://arthuredelstein.github.io/tordemos/resource-locale.html) | resource:// URIs leak information test page | `N/A` | `No` |
| [Resource://URI](https://www.browserleaks.com/firefox) | Resource://URI check for Firefox | `N/A` | `No` |



## Web API Test

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Permission Site](https://permission.site/) | A site to test the interaction of web APIs and browser permissions.  | `No` | `Partial`, [source code](https://github.com/chromium/permission.site) |



## SSL/TLS, RSA & SSH Test

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Bad SSL](https://badssl.com/) | Check against Bad SSL attack | `N/A` | `No` |
| [FREAK Attack - Client Check](https://freakattack.com/clienttest.html) | Client-side FREAK attack check | `N/A` | `No` |
| [Heartbleed Test](https://filippo.io/Heartbleed/) | Heartbleed attack Test | `N/A` | `No` |
| [RC4 Fallback Test](https://rc4.io/) | Is you browser still using obsolete and weak RC 4? | `N/A` | `No` |
| [How's My SSL](https://www.howsmyssl.com/) | Check your SSL or anothers page SSL configuration | `Yes` | `Yes` |
| [SSL Cipher Suite Details](https://cc.dcsec.uni-hannover.de/) | SSL Cipher Suite Check which also shows lots of Details | `N/A` | `No` |
| [Weak Diffie-Hellman and the Logjam Attack](https://weakdh.org/) | Diffie-Hellman attack Test | `N/A` | `No` |
| [The ROBOT Attack](https://robotattack.org/#check) | ROBOT Attack Test and Tool | `No` | `No` [ROBOT Attack checking tool](https://github.com/robotattackorg/robot-detect) (Open Source) |
| [SSH Audit](https://github.com/arthepsy/ssh-audit) | Check your SSH configuration and audit it | `No` | `No` (Open Source) |
| [Fortify](https://www.fortify.net/sslcheck.html) | SSL / TLS check | `Yes`, 1 week. | `Yes` | 
| [Symantec](https://cryptoreport.websecurity.symantec.com/checker/views/sslCheck.jsp) | Symantec SSL Check | `Yes`, 1 month. | `Yes` |



## Do Not Track (DNT), Evercookie, Headers, Javascript,...

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [BrowserRecon (Header/HTTP) Test](http://www.computec.ch/projekte/browserrecon/?s=scan) | Browser Header Check | `N/A` | `No` |
| [What Is My Referer?](https://www.whatismyreferer.com/) | Check your Browser Referer | `Yes` | `Yes` |
| [Browser Referer Headers](https://www.darklaunch.com/tools/test-referer) | Another Browser Referer Check | `N/A` | `No` |
| [Do Not Track Test](https://www.browserleaks.com/donottrack) | Does my Browser sends DNT? | `No` | `Yes` |
| [Evercookie Test](http://samy.pl/evercookie/) | Evercookies Test | `N/A` | `No` |
| [JavaScript Browser Information](https://www.browserleaks.com/javascript) | Basic JavaScript Browser check | `Yes` collects an offline database| `Yes` |
| [Popup Blocking Tests](http://www.kephyr.com/popupkillertest/index.html) | Test your Browser against popups | `N/A` | `Yes` |
| [Redirect Page Test](https://jigsaw.w3.org/HTTP/300/Overview.html) | Redirect Page Test | `Yes` collects an offline database| `Yes` |
| [System Fonts Detection Test](https://www.browserleaks.com/fonts) | Detect which Fonts your Browser sends away | `No` | `Yes` |
| [FluxFonts](https://ctrl.blog/entry/fluxfonts) | Browser Font Test Page | `N/A` | `No` |
| [JavaScript/CSS Font Detector](http://www.lalit.org/lab/javascript-css-font-detect/) | CSS and JavaScript based Font Detector | `N/A` | `Yes` |
| [Universal Plug n'Play (UPnP) Internet Exposure Test](https://www.grc.com/x/ne.dll?rh1dkyd2) | Detect UPnP based leaks | `No` | `No` |
| [JavaScript: PasteJacking](https://www.sempervideo.de/pastejacking/) | PasteJacking Test | `No` | `No` |
| [Punycode converter](https://www.punycoder.com/) | Punnycode Converter Tool | `No` | `No` |
| [Unique Machine](http://uniquemachine.org/) | Is your Machine unqiue? | `No` | `No` [Source Code](https://github.com/Song-Li/cross_browser) |
| [Mozilla Observatory](https://observatory.mozilla.org/) | `Yes` Mozilla collects all tests in a database 'to improve their products' they also use their findings in Ghostery (Clicks) and other products | `No` |
| [PrivacyScore](https://privacyscore.org/) | Which Score has your privacy setup? | `Yes` | `Yes` |
| [CryptCheck](https://tls.imirhil.fr) | Simple Domain, TLS, SSH checks | `No` | `No` |
| [Qualys SSL Labs](https://www.ssllabs.com/ssltest/) | SSL Test, eMail and Domain tools | `N/A` | `No` |
| [securityheaders.io](https://securityheaders.io) | URL/Domain Scan sponsored by Sophos | `N/A` | `No` |
| [Hardenize](https://www.hardenize.com) | Header, Browser check | `Yes` collects data and shares them | `No` |
| [Google Chrome drive-by exploit tester](http://www.sempervideo.de/chrome-driveby/) | Drive-by test for Chrome weakness | `No` | `No` |
| [The Privacy.net Analyzer](http://analyze.privacy.net) | Basic Header check which also provides several other tools | `Yes` collects an offline database | `No` |
| [Spectre Vulnerability Check](http://xlab.tencent.com/special/spectre/spectre_check.html) | Spectre Vulnerability Check | `No` but holes a offline database it's unclear if it's sold or shared | `No` |
| [Are You Trackable?](http://ubercookie.robinlinus.com/) | How trackable is your Browser? |  `No` | `No` [Source Code](https://github.com/RobinLinus/ubercookie)| 
| [Ubercookie Test](http://jcarlosnorte.com/assets/ubercookie/) | Ubercookie test | `Yes` collects an offline database | `No` |
| [CSS Exfil Vulnerability Tester](https://www.mike-gualtieri.com/css-exfil-vulnerability-tester) | The page tests to see if your browser is vulnerable to Cascading Style Sheets (CSS) data leakage. If you are vulnerable, one way to protect yourself is to install the CSS Exfil Protection plugin for your browser. | `No` | `No` | 
| [CSS History Leak](http://lcamtuf.coredump.cx/yahh/) | CSS History Leak check | `N/A` | `No` |


## DNSSEC Test

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [DNSSEC Resolver Test](http://dnssec.vs.uni-due.de/) | Test the Resolver if it supports DNSSEC | `N/A` | `No` |
| [DS Algorithm Test](https://rootcanary.org/test.html) | Check if DNSSEC is weak against DS | `N/A` | `No` |


## Government Internet Speed Test

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Breitbandmessung](http://breitbandmessung.de) | Official German Internet Speed Test | `Yes` collects an online database shares and sells them to ISP's and others you need to agree in everything before you can use it | `Yes` |


## Mouse Rate/Fingerprint Check

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Enotus mouse test](http://enotus.at.tut.by/Articles/MouseTest/index.html) | Original Tracking speed and polling rate test | `No` | `No` Page down but mirrored here under /Offline |
| [Outerspace's Max IPS logger](http://maxouterspace.com/) | Tracking speeds and will show if theres negative/positive acceleration when you hit a certain speed | `N/A` | `No` |
| [Mouse Rate Checker](http://tscherwitschke.de/old/download.html) | Simple polling rate detection | `N/A` | `Yes` |
| [Mouse reaction time tester](http://www.humanbenchmark.com/tests/reactiontime) | Online mouse reaction test | `Yes` collects an online statistic database | `No` |


## Keyboard

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Javascript Key Event Test Script](http://unixpapa.com/js/testkey.html) | Basically a JS keylogger check | `N/A` | `Yes` |
| [JavaScript Event KeyCode Test Page](http://www.asquare.net/javascript/tests/KeyCode.html) | Another keystroke test | `N/A` | `Yes` |
| [Keyboard Event Viewer]( https://w3c.github.io/uievents/tools/key-event-viewer.html) | `N/A` | `No` |


## Advanced Fingerprint Tests

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Am I Unique?](https://amiunique.org/fp) | Is your Machine / Browser unique? | `N/A` | `Yes` |
| [Browser Spy](http://browserspy.dk/) | Multiple Browser Tests | `N/A` | `Yes` |
| [Cross Browser Fingerprinting Test](http://fingerprint.pet-portal.eu/) | Multiple Browser Test | `N/A` | `Yes` User must to disable its ad-blocker! |
| [Jondonym Full Anonymity Test](http://ip-check.info/?lang=en) | The first and original anonymity test | `No` | `Yes` |
| [Panopticlick](https://panopticlick.eff.org/) | The most well-known Browser Fingerprint check by EFF | `Yes` collects stats and stores them in a database | `Yes` |
| [Browserprint.Info](https://browserprint.info/test) | Another JavaScript based Fingerprinting Test |`Yes` collects stats and stores them in a database | `Yes` |
| [Browserprint check](https://fingerprint.pet-portal.eu/) | Another advance fingerprinting check | `No` | `Yes` - Currently (?) Offline |
| [PC Flank](http://www.pcflank.com/index.htm) | Random Browser Check | `N/A` | `Yes` |
| [Onion Leak Test](http://cure53.de/leak/onion.php) | Check your .onion | `N/A` | `Yes` |
| [Whoer](https://whoer.net/) | Advance Browser check | `Yes` Sells the results | `Yes` for advance informations/tests |
| [Popup Test](http://www.popuptest.com/) | Check how good your Browser performs against Popups | `N/A` | `Yes` |
| [Privacy Check](http://do-know.com/privacy-test.html) | Another overall Browser header/leak test | `Yes` | `Yes` |
| [Audio Fingerprint Test](https://audiofingerprint.openwpm.com/) | The original audio fingerprint test | `No` | `Yes` ([Source Code](https://github.com/Gitoffthelawn)) |
| [Browser 'auto-download' Security Vulnerability](https://binaer.xyz/haifei-li/test.html) | Check Chrome, IDM and other Downloader against a security attack | `N/A` | `No` |
| [Check2IP](http://check2ip.com/) | One of the oldest advance Browser/IP tests | `No` | `Yes` only for advance tests but also works without |
| [HTML5 Canvas Fingerprinting](https://browserleaks.com/canvas) | Canvas HTML5 API Browser Test | `N/A` | `Yes` | 
| [5who](http://5who.net/?type=extend) | Multiple tests | `N/A` | `Yes` |
| [Punycode](https://www.xn--80ak6aa92e.com) | See the [Article](https://www.xudongz.com/blog/2017/idn-phishing/) | `N/A` | `No` |


## HTTP Strict Transport Security (HSTS)

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Chromium's HSTS preload list submission website](https://hstspreload.org) | Chromium's HSTS preload list submission website | `N/A` | `N/A` |
| HSTS [sniffly](http://zyan.scripts.mit.edu/sniffly/) | A practical timing attack to sniff browser history using HSTS in Chrome and Firefox. Please disable HTTPS Everywhere for best results. | `N/A` | `N/A` |


## Tor Network & Fingerprint Test

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [TorCheck at Xenobite.eu](https://torcheck.xenobite.eu/index.php) | Advance Tor Network Check | `No` | `Yes` |
| [Tor Fingerprint Test](https://tor.triop.se/) | Basic Tor Network Check | `N/A` | `No` |


## Cryptography Test

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- |
| [Shattered SHA1 attack](https://shattered.io) | SHA1 collusion attack example | `No` | `No` |


## ISP Throttling check

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- | 
| [Internet Health Test](https://www.battleforthenet.com/internethealthtest/) | Test if your ISP is throttling you | `N/A` | `No` |
| [BitTorrent Traffic Shaping](https://neubot.nexacenter.org/download) | Check if your ISP is throttling BitTorrent Traffic | `N/A` | `No` |
| [Neubot](https://neubot.nexacenter.org/download) | Tool to check if your ISP is throttling your download speed | `N/A` | `No` |
| [The Internet Health Test](https://www.battleforthenet.com/internethealthtest/) | Test if your ISP is throttling you | `Yes` collects an database and possible sells it (needs confirmation) | `No` |


## Web Search Engine which can show & inspect the source code

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- | 
| [Source Code Search Engine](https://publicwww.com) | Inspect the Page Source Code | `Yes` logs and collect databases | `Yes` |


## Firewall Test

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- | 
| [Test your Metal](http://metal.fortiguard.com/tests/) | Check your firewall online against known ports | `Yes` logs and collect databases | `Yes` |
| [Port Checker](https://portchecker.co/) | Check your Firewall against known or custom ports | `Yes` logs and collect databases | `Yes` |
| [ShieldsUp!](https://www.grc.com/faq-shieldsup.htm) | Check your Firewall against known or custom Ports | `No` | `No` |
| [PenTest yourself. Don't get hacked](https://pentest-tools.com/home) | Check your Firewall against a pre-made list | `N/A` | `No` |
| [HackerWatch](https://www.hackerwatch.org/probe/) | Check your Firewall against a pre-made list | `Yes` collects an statistic offline database  | `Yes` |
| [Hacker Target](https://hackertarget.com/firewall-test/) | Check your Firewall against a pre-made list | `Yes` collects an statistic offline database  | `Yes` |
| [CanYouSeeMe.org](http://canyouseeme.org/) | Basic Firewall test | `N/A` | `No` |


## Torrent

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- | 
| [ipMagnet](http://ipmagnet.services.cbcdn.com/) | Magnet IP expose check | `N/A` | `No` |
| [Check My Torrent IP](https://torguard.net/checkmytorrentipaddress.php) | Check which IP your Torrent Network sees | `Yes` collects a statistic database | `No` |
| [I know what you downloaded](https://iknowwhatyoudownload.com/en/peer/) | Check what your peer sees about you | `N/A` | `No` |
| [IP Magnet Test](http://ipmagnet.services.cbcdn.com/) | Allows you to see which IP address your BitTorrent Client is handing out to its peers and trackers! | `No` | `No` |


## Ransomware Decrypter 

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- | 
| [NoMoreRansom](https://www.nomoreransom.org) | Official against Ransomware page for help, decrypter and information | `N/A` | `No` |
| [Free Ransomware Decryptors - Kaspersky Lab](https://noransom.kaspersky.com/) | Kaspersky's Ransomware Help Page | `N/A` | `N/A` |
| [Avast Free Ransomware Decryption Tools](https://www.avast.com/ransomware-decryption-tools) | Free Ransomware Decryption Tools by Avast | `N/A` | `N/A` |
| [Emsisoft Decrypter Tools](https://decrypter.emsisoft.com/) | Emsisoft Decrypter | `N/A` | `N/A` |
| [Trend Micro Ransomware File Decryptor Tool](https://success.trendmicro.com/solution/1114221-downloading-and-using-the-trend-micro-ransomware-file-decryptor) | Several decrypter powered by TrendMicro | `N/A` | `N/A` |
| [Heimdal Decrypter Tools](https://heimdalsecurity.com/blog/ransomware-decryption-tools/) | Bunch of decrypter utilities | `N/A` | `N/A` |
| [Free Ransomware Decryption Tools](https://www.avg.com/en-ww/ransomware-decryption-tools) | Decrypter tools by Avast | `N/A` | `N/A` |
| [Download All Known Ransomware Decryption Tools](https://www.mdsny.com/decryption-tools/) | MDS collection of all known Ransomware decryoter | `N/A` | `N/A` |


## Identify theft check

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- | 
| [Have I Been Pwned](https://haveibeenpwned.com) | Check if your identiy (email etc) was used/stolen by someone else | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `Partial` |
| [Shodan.io](https://www.shodan.io/) | Search for devices, vuln. etc | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `Yes` |
| [New York Attorney General Eric Schneiderman tool](https://ag.ny.gov/fakecomments) | Tool which check fake comments based on a database of known fakers | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `N/A` |


## Browser Benchmarks

Keep in mind that a Browser Benchmark doesn't reflect the real-world performance of a website, as explained over [here](https://news.softpedia.com/news/google-to-drop-support-for-octane-browser-benchmark-514942.shtml).

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- | 
| [Speedometer](http://browserbench.org/Speedometer/) | JavaScript based Browser Benchmark | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `Yes` |
| [ARES 6](http://browserbench.org/ARES-6/) | JavaScript based Browser Benchmark | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `Yes` |
| [Motion Mark](http://browserbench.org/MotionMark/) | JavaScript based Browser Benchmark | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `Yes` |
| [JetStream](http://browserbench.org/JetStream/) | JavaScript based Browser Benchmark | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `Yes` |
| [Lite Brite](https://testdrive-archive.azurewebsites.net/Performance/LiteBrite/) | JavaScript based Browser Benchmark | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `Yes` |
| [Octane](https://chromium.github.io/octane/) | JavaScript based Browser Benchmark | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `Yes` |
| [Dromaeo](http://dromaeo.com) | JavaScript based Browser Benchmark | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `Yes` |
| [Acid 3](http://acid3.acidtests.org/) | JavaScript based Browser Benchmark | `Yes` collects an database (need confirmation if sold to 3rd-parties) | `Yes` |


## Sandboxes Virus/Malware/HTTP analyzer 

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- | 
| [BitBlaze](http://bitblaze.cs.berkeley.edu/) | The BitBlaze Binary Analysis Platform | `No`, it's open source | `No` |
| [Hybrid Analysis](https://www.hybrid-analysis.com/) + [Mirror](https://www.reverse.it/) | Free Malware analysis service for the community that detects and analyzes unknown threats using a unique Hybrid Analysis technology | `N/A` | `Yes` for the WebInterface. |
| [Jevereg](http://jevereg.amnpardaz.com/) | Jevereg analyses the behavior of potential malicious executables | `N/A` | `No` |
| [Sunbelt Sandbox](https://www.threattrack.com/malware-analysis.aspx) | Dig Deep with Malware Analysis | `Yes` Tracks IP, collects data and sells them. | `Yes` |
| [ThreatExpert](http://www.threatexpert.com/) | ThreatExpert is an advanced automated threat analysis system designed to analyze and report the behavior of computer viruses, worms, trojans, adware, spyware, and other security-related risks in a fully automated mode. | `N/A` | `N/A` |
| [ViCheck](https://vicheck.ca/) | Advanced Detection Tools to Stop Malware | `N/A` | `No` |
| [detux](https://detux.org/) | Multiplatform Linux Sandbox | `N/A` | `No` |
| [Nviso](https://apkscan.nviso.be/) | Nviso APK scan | `N/A` | `Yes` |
| [Java Script Beatify](http://jsbeautifier.org/) | Beautify, unpack or deobfuscate JavaScript and HTML, make JSON/JSONP readable, etc. | `N/A` | `Yes` |
| [PDF Examiner](http://www.malwaretracker.com/pdf.php) | Scan PDF files | `N/A` | `No` |
| [Rex Swain's HTTP Viewer](http://www.rexswain.com/httpview.html) | See exactly what an HTTP request returns to your browser | `N/A` | `N/A` |
| [JSUNPACK](http://jsunpack.jeek.org/dec/go) | jsunpack was designed for security researchers and computer professionals | `N/A` | `N/A` |
| [Google VirusTotal](https://www.virustotal.com/) | Analyze suspicious files and URLs to detect types of malware, automatically share them with the security community. | `Yes`, see [privacy policy](https://support.virustotal.com/hc/en-us/articles/115002168385-Privacy-Policy). | `N/A` |
| [Jotti](https://virusscan.jotti.org/) | Jotti's malware scan is a free service that lets you scan suspicious files with several anti-virus programs. | `Yes`, see [Privacy Policy](https://virusscan.jotti.org/en-US/doc/privacy). | `N/A` |


# Online Link Checkers

| **Page or Addon** | **Description** | **Collects or sells user data?** | **Requires activated JavaScript**
| --- | --- | --- | --- | 
| [Dr.Web Online Scanner](https://vms.drweb-av.de/online/) | URL link checker | `Yes` | `Yes` |
| [Google Safe Browsing](https://transparencyreport.google.com/safe-browsing/search?url=putyourlinkhere.com) | Change putyourlinkhere.com to url you want to check! | `Yes`, see [here](https://support.google.com/transparencyreport/). | `Yes` |
| [Norton Safe Web](https://safeweb.norton.com/) | Look up a site. Get our rating. | `Yes`, see [privacy policy](http://nortonsafe.search.ask.com/docs/privacy?geo=&prt=cr&o=APN11908&chn=&ver=) | `Yes` |
| [URL Void](http://www.urlvoid.com/) | Website Reputation Checker Tool | `Yes`, see [terms and privacy](http://www.privalicy.com/privacy-policy/21312665/) | `Yes` |
| [vURL Online](http://vurl.mysteryfcm.co.uk/) | Quickly and safely dissect malicious or suspect websites | `Yes`, IP address of the requesting computer is recorded along with the URL accessed. Stored for 1 week. | `No` |
| [Online Link Scan](http://onlinelinkscan.com/) | Prevent infection and data theft with Online Link Scan. | `N/A` | `N/A` |
