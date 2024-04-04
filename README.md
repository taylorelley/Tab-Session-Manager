# <sub><img src="/src/icons/icon.svg" width=64px height=64px></sub> Tab-Session-Manager

#### Save and restore the state of browser windows and tabs. It also supports automatic saving.

<img src="https://raw.githubusercontent.com/taylorelley/Tab-Session-Manager/master/other/promotion/screenshots/popup.png" width="640px">

## Developing

> Required: Node 18.17.1

1. Clone the repository `git clone https://github.com/taylorelley/Tab-Session-Manager`  
2. Create the file `src/credentials.js`  
  ```src/credentials.js
  export const clientId = "xxx"
  export const clientSecret = "xxx"
  ```
3. Run `npm install`
4. Run `npm run watch-dev`

### Load the extension in Chrome

1. Open Chrome browser and navigate to `chrome://extensions`
2. Select "Developer Mode" and then click "Load unpacked extension..."
3. From the file browser, choose to `tab-session-manager/dev/chrome`

### Load the extension in Firefox

1. Open Firefox browser and navigate to `about:debugging`
2. Click "Load Temporary Add-on" and from the file browser, choose `tab-session-manager/dev/firefox`

## Privacy Policy

[Privacy Policy](https://tab-session-manager.sienori.com/privacy-policy) of Tab Session Manager
