![STE-Electron](https://socialify.git.ci/FireStreaker2/STE-Electron/image?description=1&forks=1&issues=1&logo=https%3A%2F%2Fste.firestreaker2.gq%2Ffavicon.png&name=1&owner=1&pattern=Formal%20Invitation&pulls=1&stargazers=1&theme=Dark)

## Setup
### Method 1: Website
The <a href="https://electron.ste.firestreaker2.gq">website</a> contains a couple ways for you to set this up. An installer, Prebuilt Binaries, and another one that leads you back here.

### Method 2: Manually Compiling
This is for the people that don't want to get a virus somehow, and also for the people that want to do this for some reason.
```bash
$ git clone https://github.com/FireStreaker2/STE-Electron.git
$ cd STE-Electron
$ npm i
$ npm run make
```
After everything has loaded, your directory should look something like this:
```
STE-Electron
├── node_modules/
├── out/
├── src
|   ├── public
|   |   ├── favicon.png
|   |   ├── index.css
|   |   ├── index.html
|   |   ├── index.js
|   └── index.js
├── .gitignore
├── forge.config.js
├── LICENSE
├── package-lock.json
├── package.json
└── README.md
```
You then want to navigate to ``out/ste-electron-win32-x64/``, and inside you'll find all of the binaries!

## Credits
<a href="https://electronjs.org/">Electron</a>

## License
<a href="https://github.com/FireStreaker2/STE-Electron/blob/main/LICENSE">MIT</a>