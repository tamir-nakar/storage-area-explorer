# Storage Area Explorer (Manifest V3)

> Note: This is a forked version of the original Storage Area Explorer by Alexey Bykov, released under the MIT License. The original extension had not been updated for a long time and was deprecated from the Chrome Web Store due to its use of Manifest V2. This version has been upgraded to Manifest V3 to ensure compatibility with modern Chrome browsers.


Chrome Developer Tools extension which allows to:

   * inspect [Storage Area](http://developer.chrome.com/apps/storage.html) of [Chrome Packaged Apps](http://developer.chrome.com/apps/about_apps.html)
   * inspect HTML5 local&session storage
   * export storage contents as JSON into clipboard or file
   * import storage contents from clipboard or file

~~Install from latest stable 0.4.3 version from [Chrome Store](https://chrome.google.com/webstore/detail/storage-area-explorer/ocfjjjjhkpapocigimmppepjgfdecjkb)~~ *(Original version no longer available)*

## Manifest V3 Upgrade

This fork includes the following improvements:
- ✅ Upgraded to **Manifest V3** for Chrome compatibility
- ✅ Updated background scripts to service worker
- ✅ Modern clipboard API with fallback support
- ✅ Updated Chrome extension APIs for future compatibility

Screen shots:

![General view](https://raw.github.com/jusio/storage-area-explorer/master/screenshots/general-view.png)
![Editing](https://raw.github.com/jusio/storage-area-explorer/master/screenshots/editing.png)
![Export](https://raw.github.com/jusio/storage-area-explorer/master/screenshots/export.png)
![Import](https://raw.github.com/jusio/storage-area-explorer/master/screenshots/import.png)
![HTML5 Local&Session storage inspection](https://raw.github.com/jusio/storage-area-explorer/master/screenshots/localStorage.png)
