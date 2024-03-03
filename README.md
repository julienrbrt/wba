# WBA

> WBA stands for Web3 Bank App. It wasn't super inspired but it's a working title for now.

WBA is a web3 bank app using Monerium API.

I am making this because I find that `monerium.app` is missing some features that I would like to have in a mobile bank app. The list of features I want to implement is the following:

- [ ] Implement Monerium API
- [ ] IBAN Contact list
- [ ] Sign transaction with password
- [ ] Sign transaction with FaceID
- [ ] Recurring SEPA payment
- [ ] Recurring crypto payment
- [ ] Notifications
- [ ] Transaction history with categories
- [ ] Export app data (except private key) to JSON.

This app will be mostly made for me, so I can use monerium as a daily driver. Additionally I always wanted to play with [Wails](https://github.com/wailsapp/wails) so that will be a good opportunity to do so. If you want a feature there that I happen to not need myself, please implement it yourself and submit a PR.

## Development

WBA is based on the official Wails Vue-TS template.

You can configure the project by editing `wails.json`. More information about the project settings can be found
here: <https://wails.io/docs/reference/project-config>

## Live Development

To run in live development mode, run `wails dev` in the project directory. This will run a Vite development
server that will provide very fast hot reload of your frontend changes. If you want to develop in a browser
and have access to your Go methods, there is also a dev server that runs on <http://localhost:34115>. Connect
to this in your browser, and you can call your Go code from devtools.

## Building

To build a redistributable, production mode package, use `wails build`.
