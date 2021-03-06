# samp-forums-link-fixer
~~**As of 30/11/2018 this extension is no longer needed, since YouTube links aren't blocked anymore.**~~
**YouTube links are blocked again!**

Google Chrome extension to fix censored YouTube links on the SA-MP Forums.

## Chrome Web Store Installation
The extension is published on the Chrome Web Store at: https://chrome.google.com/webstore/detail/sa-mp-forums-link-fixer/mholjpgmjkogjknijenkmomljgdalahj

## Manual Installation
1. Clone or download this repository and put the directory where you want.
2. Open the **Extension Management** page by navigating to `chrome://extensions` in the browser.
3. Enable **Developer Mode** by clicking the toggle switch next to **Developer mode**.
4. Click the **Load unpacked extension** button and select the previously mentioned directory.

## Description
- Video demonstration: https://www.youtube.com/watch?v=qBIpGo_E5YQ.
- The extension uses a page action icon shown in the browser toolbar.
- The icon will be **full-color** when users navigate to a URL that contains `forum.sa-mp.com`, showing that the extension is **active** and will be **grey-scale** when users navigate to any other URL, showing that the extension is **inactive**.
- When the extension is active, it will scan the HTML document for any hyperlinks that look like a typical censored YouTube video URL and replace the censored URL with a working one. If the hyperlink text is also censored, it will be repaired as well.
