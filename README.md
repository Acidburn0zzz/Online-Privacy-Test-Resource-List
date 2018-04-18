# - POTARC -

Privacy Online Test And Resource Compendium© project original created under the MIT license 2016 - 2018 by CHEF-KOCH and community.

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40CHEF-KOCH)](https://twitter.com/CKsTechNews)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/CHEF-KOCH)
[![Discord](https://discordapp.com/api/guilds/418256415874875402/widget.png)](https://discord.me/CHEF-KOCH)

# Privacy Online Test And Resource Compendium

This list is designed to show all available (and useful) online tests, we may not add each test if it's unclear if it collects only data to hand/sell it to 3th-party developer or people which pay for it to use it for 'bad' things. 

I see this as a 'community' based project since everyone can contribute and no one ever will excluded (only with good reasons like spamming, ...). I/we not accept any donations because we all doing this in our free time and it's up to everyone. The information should be available for free for everyone. 


**Known Fingerprinting Techniques:**
* [OSI model fingerprints](https://searchnetworking.techtarget.com/tip/OSI-Securing-the-Stack-Layer-4-Fingerprinting) (based on [HTTP](https://github.com/wireghoul/lbmap), Header, User Agent, Firewall, ...)
* [CPU Fingerprint](http://yinzhicao.org/TrackingFree/crossbrowsertracking_NDSS17.pdf)
* [Mouse & CPU fingerprinting](http://jcarlosnorte.com/security/2016/03/06/advanced-tor-browser-fingerprinting.html)
* [User fingerprinting problem (Canvas, IP, ...)](https://en.wikipedia.org/wiki/Canvas_fingerprinting)
* Screen resolution (this possible will never be fixed since it would break too much)
* [UberCookie](http://ubercookie.robinlinus.com/faq.html)/[Cookies](https://en.wikipedia.org/wiki/HTTP_cookie)/[EverCookie](https://en.wikipedia.org/wiki/Evercookie)/[Supercookies](https://en.wikipedia.org/wiki/HTTP_cookie#Supercookie)
* [Database fingerprints](https://github.com/Valve/fingerprintjs2)
* Measuring time (Timezone/[NTP](http://www.securityweek.com/ntp-servers-exposed-long-distance-wireless-attacks))
* getClientRects fingerprinting via [DOM](http://www.water.ca.gov/waterquality/docs/Fingerprinting%20Sources%20of%20DOM%20-%20Ngatia.pdf)
* Hardware implemented fingerprint methods such as [hardware based DRM](https://docs.microsoft.com/en-us/windows/uwp/audio-video-camera/hardware-drm)
* [Plugin/Extension tracking](https://webdevwonders.com/detecting-browser-plugins/) (Silverlight, Adobe Flash, ...)
* [Tor node detection](https://check.torproject.org/)
* [DNS leakage or bypasses](https://www.dnsleaktest.com/what-is-a-dns-leak.html)
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
* Several HTTP authorization detection (not fixable because it's protocol depending + meta-data)
* Stuff which is documented and mentioned over [here](https://github.com/CHEF-KOCH/NSABlocklist).
* [CPU Starvation Attacks](https://msdn.microsoft.com/en-us/library/ee810608(v=cs.20).aspx)
* [Memory Starvation Attacks](https://msdn.microsoft.com/en-us/library/ee810601(v=cs.20).aspx)
* [Resource Starvation Attacks](https://msdn.microsoft.com/en-us/library/ee798408(v=cs.20).aspx)
* [Network Bandwidth Attacks](https://msdn.microsoft.com/en-us/library/ee798452(v=cs.20).aspx)
* [ISP throttling checks](https://thenextweb.com/apps/2015/05/21/quick-test-shows-if-isps-are-secretly-throttling-your-internet-speeds/)
* CDN {Web Cache Deception Attack](https://omergil.blogspot.ch/2017/02/web-cache-deception-attack.html)
* [Extension system based attacks](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-sanchez-rola.pdf)
* [NoCoin](https://github.com/keraf/NoCoin), prevents background mining via opt-in
* [Urchin Tracking Module (UTM)](https://support.google.com/urchin/answer/28307?hl=en)
* [uBeacons](https://www.ubuduasia.com/single-post/2015/12/02/Leverage-Data-Analytics-to-reevaluate-your-marketing-effort-using-uBeacons-)
* Fake identity, Identify theft (not fixable) & Fake Comments
* Crooked Style Sheets
* [User agent detection](https://en.wikipedia.org/wiki/Usage_share_of_web_browsers#User_agent_spoofing)
* [Zero With Detection](https://umpox.github.io/zero-width-detection/)
* [Acoustic fingerprinting](https://en.wikipedia.org/wiki/Acoustic_fingerprint)
* [Automatic content recognition](https://en.wikipedia.org/wiki/Automatic_content_recognition)
* [Canvas fingerprinting](https://en.wikipedia.org/wiki/Canvas_fingerprinting)
* [Digital video fingerprinting](https://en.wikipedia.org/wiki/Digital_video_fingerprinting)
* [Public key fingerprint](https://en.wikipedia.org/wiki/Public_key_fingerprint)
* [Common Spoofing attacks](https://en.wikipedia.org/wiki/Spoofing_attack)


**Fixed within the Browser (ensure you using the latest product [always])**
* SSL / TLS (ciphers) [if you only browsing on pages like GitHub ~ you can even more '[harden](https://tools.ietf.org/html/draft-sheffer-tls-bcp-00)' it]
* OpenSSL fixed (heartbleed,...) 
* Tor (several fingerprints still possible, it's on the todo and will be fixed soon)
* Java/Adobe Flash, both are dead -> HTML5
* HTML5 several stuff like Canvas, Font, ... (will never be fixed, use addons)
* Cookies in general are not fixable since your page may need it, Amazon for shopping as an example (addons/filter-lists may help to whitelist).
* CPU, mouse wheel fingerprinting which needs to be fixed also within the OS (still open)
* MAC address leakage - disable IPv6 (if not necessary/needed)
* WebRTC since Chrome 48+ and Firefox 42+, both getting an new menu to allow it per-page (whitelist) [there exist also for both several addons, workarounds to compile it without WebRTC support)
* PopUps are (if not Canvas/JS related) not anymore possible, you see a permission dialog or can control this behavior directly via Browser settings
* [Audio fingerprint tests](https://github.com/worldveil/dejavu), [example](https://github.com/dpwe/audfprint).
* .... 

**How to handle this?**

Collection of [device fingerprints](https://en.wikipedia.org/wiki/Device_fingerprint) from web clients (browser software) relies on the availability of JavaScript or similar client-side scripting language for the harvesting of a suitably large number of parameters. Overall this means if only one or a small of things are detectable it not automatically reveals your true identify, but all together is pretty dangerous.

Some mentioned services & pages collect the results and store it offline, some even sell the results to 3rd-parties! I'm not responsible for this behavior, the list will add an indicator for services which doing it soon.


## Contribution

See CONTRIBUTING.md


## Obsolete Add-ons & Plugin Tests

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


## Add-ons e10s check

Firefox Compatible check:
https://www.arewee10syet.com/


## eMail

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

Check Your GPG Fingerprints
https://evil32.com/


## Certificate

Revocation Awareness Test:
https://www.grc.com/revocation.htm


## Crypto mining

MALWARE DETECTED WITH THREAT EMULATION
http://www.cpcheckme.com/checkme/


## HTML5 Test

Basic HTMl5 Video and Audio tester (works without JS or Plugins):
http://tools.woolyss.com/html5-audio-video-tester/

Battery Status API:
http://pstadler.sh/battery.js/

Canvas Fingerprinting:
https://www.browserleaks.com/canvas

canvas.toBlob test:
https://blueimp.github.io/JavaScript-Canvas-to-Blob/test/

get.Image Canvas test:
http://tutorialspark.com/html5/HTML5_Canvas_get_Image_Data_Demo.php

Battery Status API:
https://pazguille.github.io/demo-battery-api/

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

WebRTC Leak Test:
https://diafygi.github.io/webrtc-ips/

WebRTC Test:
https://test.webrtc.org/

WebRTC What's My IP Check:
http://whatismyipaddress.com/webrtc-test

Anonymster WebRTC check:
https://anonymster.com/web-rtc-leak-test/

HTML5 Security Cheatsheet:
https://html5sec.org/

Chromium HTML5 audio/video tester:
https://tools.woolyss.com/html5-audio-video-tester/


## CSS 

Crooked Style Sheets:
http://crookedss.bplaced.net/ ([Source](https://github.com/jbtronics/CrookedStyleSheets))


## IP & DNS Leak Tests

GeoTek Datentechnik - Web Privacy Check:
https://ipinfo.info/html/privacy-check.php

DoiLeak:
https://www.doileak.com/

IP Leak:
https://ipleak.net/

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

Mirai Vulnerability Scanner:
https://www.incapsula.com/mirai-scanner/

Galhi US Test:
http://ip.galih.us

Check your current IP:
http://checkip.dyn.com


## Privacy Management

Google Account History:
https://www.google.com/settings/accounthistory

Facebook Activity Log:
https://www.facebook.com/me/allactivity

YouTube Video History / Search History:
https://www.youtube.com/feed/history

Microsoft Account Credentials Leak vulnerability check:
https://msleak.perfect-privacy.com/

Checks website reputation and additional security related infos:
https://github.com/andersju/webbkoll

Browser Extension and Login-Leak Experiment:
https://extensions.inrialpes.fr/

Hide my Footprint:
https://hmfp.absolutedouble.co.uk/

Browsers leak installed extensions PoC:
https://github.com/earthlng/testpages

Information Disclosure on IE:
https://www.cracking.com.ar/demos/ieaddressbarguess/

ETag:
http://lucb1e.com/rp/cookielesscookies/

Overview of all supported Two Factor Auth (2FA) pages:
https://twofactorauth.org/


## Resource:// URIs checks 

Arthured Elstein resource:// URIs leak information page:
https://arthuredelstein.github.io/tordemos/resource-locale.html


## SSL Test

Bad SSL:
https://badssl.com/

FREAK Attack - Client Check:
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


## RSA Test

The ROBOT Attack
https://robotattack.org/#check ([ROBOT Attack checking tool](https://github.com/robotattackorg/robot-detect))


## SSH Test

SSH Audit:
https://github.com/arthepsy/ssh-audit


## Random Tests (DNT, Evercookie, Headers, Javascript,...)

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

FluxFonts:
https://ctrl.blog/entry/fluxfonts

JavaScript/CSS Font Detector:
http://www.lalit.org/lab/javascript-css-font-detect/

Universal Plug n'Play (UPnP) Internet Exposure Test:
https://www.grc.com/x/ne.dll?rh1dkyd2

JavaScript: PasteJacking:
https://www.sempervideo.de/pastejacking/

Punycode converter:
https://www.punycoder.com/

Unique Machine:
http://uniquemachine.org/ ([Source](https://github.com/Song-Li/cross_browser))

Mozilla Observatory:
https://observatory.mozilla.org/

PrivacyScore:
https://privacyscore.org/

CryptCheck:
https://tls.imirhil.fr

Webbkoll ([source](https://github.com/andersju/webbkoll)):
https://webbkoll.dataskydd.net/en

Qualys SSL Labs:
https://www.ssllabs.com/ssltest/

securityheaders.io:
https://securityheaders.io

Hardenize:
https://www.hardenize.com

Google Chrome drive-by exploit tester:
http://www.sempervideo.de/chrome-driveby/

The Privacy.net Analyzer:
http://analyze.privacy.net

Spectre Vulnerability Check:
http://xlab.tencent.com/special/spectre/spectre_check.html

Are You Trackable?:
http://ubercookie.robinlinus.com/ ([Source](https://github.com/RobinLinus/ubercookie))

Ubercookie Test:
http://jcarlosnorte.com/assets/ubercookie/


## DNSSEC

DNSSEC Resolver Test:
http://dnssec.vs.uni-due.de/

DS Algorithm Test:
https://rootcanary.org/test.html


## Mouse 

Enotus mouse test (Tracking speed and polling rate): 
http://enotus.at.tut.by/Articles/MouseTest/index.html (link broken but the tool is mirrored)

Outerspace's Max IPS logger (Tracking speeds and will show if theres negative/positive acceleration when you hit a certain speed):
http://maxouterspace.com/

Mouse Rate Checker (polling rate):
http://tscherwitschke.de/old/download.html

Mouse reaction time tester:
http://www.humanbenchmark.com/tests/reactiontime


## Keyboard

Javascript Key Event Test Script
http://unixpapa.com/js/testkey.html

JavaScript Event KeyCode Test Page
http://www.asquare.net/javascript/tests/KeyCode.html


## Advanced Tests

Am I Unique?:
https://amiunique.org/fp

Browser Spy (Multiple Tests):
http://browserspy.dk/

Cross Browser Fingerprinting Test (User must to disable its ad-blocker!):
http://fingerprint.pet-portal.eu/

Jondonym Full Anonymity Test:
http://ip-check.info/?lang=en

Panopticlick:
https://panopticlick.eff.org/

Browserprint.Info:
https://browserprint.info/test

Browserprint check (offline):
https://fingerprint.pet-portal.eu/

PC Flank:
http://www.pcflank.com/index.htm

Onion Leak Test:
http://cure53.de/leak/onion.php

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

Check2IP:
http://check2ip.com/


## HTTP Strict Transport Security (HSTS)

Chromium's HSTS preload list submission website:
https://hstspreload.org


## Tor Network & Finterprint checks

TorCheck at Xenobite.eu:
https://torcheck.xenobite.eu/index.php

Tor Fingerprint Test:
https://tor.triop.se/


## Cryptography

Shattered SHA1 attack (SHA1 collusion example):
https://shattered.io


## Chrome WebRTC check

Web RTC Chrome vulnerability check:
https://internet-israel.com/internet_files/webrtc/index.html ([Bug 709952](https://bugs.chromium.org/p/chromium/issues/detail?id=709952))


## ISP Throttling check

BitTorrent Traffic Shaping:
https://neubot.nexacenter.org/download

Glasnost:
http://broadband.mpi-sws.org/transparency/glasnost.php

The Internet Health Test:
https://www.battleforthenet.com/internethealthtest/


## Web Search Engine which can show/inspect the source code

Source Code Search Engine:
https://publicwww.com


## Torrent

ipMagnet:
http://ipmagnet.services.cbcdn.com/

Check My Torrent IP:
https://torguard.net/checkmytorrentipaddress.php

I know what you downloaded:
https://iknowwhatyoudownload.com/en/peer/


## Ransomware

NoMoreRansom:
https://www.nomoreransom.org


## Identify theft check

Have I Been Pwned:
https://haveibeenpwned.com


## Browser Benchmarks

Speedometer:
http://browserbench.org/Speedometer/

ARES 6:
http://browserbench.org/ARES-6/

Motion Mark:
http://browserbench.org/MotionMark/

JetStream:
http://browserbench.org/JetStream/

PeaceKeeper:
http://peacekeeper.futuremark.com

Lite Brite:
https://testdrive-archive.azurewebsites.net/Performance/LiteBrite/

Octane:
https://chromium.github.io/octane/

Dromaeo:
http://dromaeo.com

Acid 3:
http://acid3.acidtests.org/


## Hardware Device Search engine

Shodan.io:
https://www.shodan.io/


## Identity check

New York Attorney General Eric Schneiderman tool:
https://ag.ny.gov/fakecomments
