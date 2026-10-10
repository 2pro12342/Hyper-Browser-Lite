# Hyper Browser Lite 
An unblocked browser as an IWA that bypasses school blockers, admin extensions, and more. 

## Features: V1.0.0 - Testing
- Multi-tab Management
- Spy Mode (Incognito mode)
- Browser URLs (Settings, History, Extensions, Bookmark Manager, Credits, etc.)
- Screen capture & Record
- Search Engine customization 
- DevTools (page inspecting, Console, Network, and Page source)
- Theme customization
- JS bookmarklets
- bookmarks & bookmark bar
- debugging urls
- Fully functional fullscreen
and more!

## Installation 
1. Download `Hyper-Browser-Lite.swbn` from releases. 
2. Open ChromeOS Settings, not the browser settings.
3. Go to `Apps` and click `Turn on isolated web apps` so it's enabled.
4. Go to `chrome://flags#enable-isolated-web-app-dev-mode` and set it to enabled, then relaunch Chrome.
5. Go to `chrome://iwa-dev` and click the `+ Intstall` button.
6. Click `Signed Bundle` and click `install`, then upload the `Hyper-Browser-Lite.swbn` file.
- Boom! you now have Hyper Browser Lite installed.

## to open the browser IWA: 
- Search for apps in the launcher (press search key or click the button in the bottom right on your desktop bar), then search for `Hyper Browser Lite`.
  
## Q&A's 
  
**Why is it the lite version instead of the full version?**
- the lite version is just the browser, the full version will have a lot more hyper features
  
**What is in the full version?**
- Hyper plus (extra hyper features; an extension store, a built-in app store, a built-in terminal/crosh app, Account adding/saving, a built-in file manager, and more), hyper tools (custom VPNs, multiple window opening, AdBlocker), and more.
  
**How is the browser unblocked?** 
- the installed browser is unblocked because the IWA cannot access Chrome, nor Chrome cannot access the IWA (that makes admin extension blockers unable to reach Hyper Browser Lite even if the setting `allow in incognito mode` is enabled). Also Hyper Browser Lite uses a thing called `Controlled Frames`, which kind of works like i-frames, but embedded content/sites blocked by Chrome is not blocked because it is controlled.
  
**How long have you been working on this project for?** 
- I have been working on this project since September 26th because I came across a repo called Kitchen Sink by ChromeOS which is a demo for IWA's.
  
**Why can't I install this like Kitchen Sink?** 
- Kitchen Sink is by ChromeOS, which explains some of it. The other part is signed `swbn` files cannot be signed by a normal developer or user. A Google admin or a Google developer has to confirm and sign your project/app to be in the user allow-install list, that is why when normally setting it up through Kitchen Sink installation steps, it won't work. More about this explanation, here: `https://developer.chrome.com/docs/iwa/allowlist`.
  
**What is an IWA?** 
- IWA stands for Isolated Web App, which basically means a web app that is contained and restricted rather than being fetched live from a site/url. this also works like an EXE file, but an IWA is highly secure and a self-contained environment.
  
## Credits 
- 2pro12342 | BOLT Studios
- BOLT Projects (this project is apart of the Hyper group)

