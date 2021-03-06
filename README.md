<h1 align="center">Firefox hardening</h1>

<h1 align="center">Sane security conscious settings</h1>

To use, place user.js in one of the following folders:
* Unix-like (hidden folder): ~/.mozilla/firefox/<profile folder> 
* Windows: C:\Users\<Username>\AppData\Roaming\Mozilla\Firefox\Profiles\yourprofile\

Notes:
* DOM storage's size has been reduced, but has not been disabled for compatibility purposes;
* webGL is turned on for my convenience;

Extensions:
* [Decentraleyes](https://github.com/Synzvato/decentraleyes)
* [HTTPS-Everywhere](https://github.com/EFForg/https-everywhere)
* [HTTPS Finder](https://github.com/kevinjacobs/HTTPS-Finder)
* [uMatrix](https://github.com/gorhill/uMatrix/) (in default-deny mode; malware lists checked)
* [uBlock by Gorhill](https://github.com/gorhill/ublock/) (non-advanced mode; all lists checked in uMatrix unchecked)


======================


![Firefox](https://fuwa.se/f/9gXXAU.png)

![Chromium*](https://fuwa.se/f/YlWsFt.png)


Chromium requires [Chameleon 0.6](https://github.com/ghostwords/chameleon) in order to change the HTTP_ACCEPT headers, as well as the user agent (although replacing the latter is trivial).

Flash users, disable font enumeration if possible (mms.cfg). Firefox users ought to use [freshplayerplugin](https://github.com/i-rinat/freshplayerplugin), a  ppapi2npapi compatibility layer that allows Firefox to use Chrome's up-to-date pepperflash.


=====================



For a user.js with more emphasis on security (occasionally at the cost of functionality, like when you completely disable DOM storage, for instance), and less emphasis on blending in, check [pyllyukko's user.js](https://github.com/pyllyukko/user.js). To compare privacy conscious user.js files, use [jm42's compare-user.js](https://github.com/jm42/compare-user.js).
