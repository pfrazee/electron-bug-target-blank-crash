# electron-quick-start

```
npm install
npm start
```

Then click "Click here for crashies."

The salient feature seems to be the `nativeWindowOpen` on the webview's webpreferences. Remove that, and the crash stops