# GoogleKeepDesktop 

Desktop app for [Google Keep][google-keep] packaged with [Electron][electron]

![](screenshot.png)

Linux
![](screenshot-linux.png)

Windows
![](screenshot-win.png)

Mac
![](screenshot-mac.png)

## Install Prebuilt Installer

Go to Release to download installer for all OS.

* Linux: GoogleKeepDesktop-linux-x64.zip (64-bit), GoogleKeepDesktop-linux-ia32.zip (32-bit)
* Mac: GoogleKeepDesktop-darwin-x64.zip
* Windows: GoogleKeepDesktop-win32-ia32.zip


## Optional: Create Electron Development

```sh
git clone https://github.com/a-lang/keep.git
cd keep
npm install
```

## Optional: Build the distribution files

Build the application for specified platform:

```sh
npm start
npm run pacakge:linux
npm run package:macos
npm run package:win
```

## License

[UNLICENSE][unlicense]

[google-keep]: https://keep.google.com
[electron]: http://electron.atom.io
[unlicense]: http://unlicense.org
