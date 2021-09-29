# Class 13

## HTML5 Storage

Previously before there was Web Storage, the only way of storing the data on the client-side was by using cookies. While using cookies there are disadvantages.

### Disadvantages to Using Cookies

1. Cookies are stored on the client-side and are transferred to the server on every request, making them less secure.
2. Cookies have a storage limit.
3. Cookies are easily disabled using browser extensions
4. Cookies slow down the the web application due to being sent with every request

Both local and Session storage have a storage limit of 5MB each and all modern web browsers support Web Storage.

### Session Storage

1. Session Storage is per browser tab. So data stored in one browser tab will not be accessible in another browser tab.
2. Each browser tab has separate session storage data.
3. Session Storage data gets cleared when we close the tab.
4. Session storage also gets cleared when we close the browser.

### Local Storage

1. Local storage is used for storing data acroos the entire application
2. Local Storage data will not get cleared even if you close the browser. Because it’s stored on your browser cache in your machine.
3. Local Storage data stored on normal browsing sessions will not be available when you open a browser in private browsing or in Incognito mode.
4. Data stored in local storage will be accessible across all the tabs or pages only for that domain.



[HOME](README.md)