## Disclaimer

This repo is a fork of [octaImage/robotjs](https://github.com/octalmage/robotjs) and is used internally at [nut-tree/nut.js](https://github.com/nut-tree/nut.js).
It is not meant to be used as a package itself.

Please refer to the original package if you plan to do so.

## Building

Please ensure you have the required dependencies before installing:

* Windows
  * windows-build-tools npm package (`npm install --global --production windows-build-tools` from an elevated PowerShell or CMD.exe)
* Mac
  * Xcode Command Line Tools.
* Linux
  * Python (v2.7 recommended, v3.x.x is not supported).
  * make.
  * A C/C++ compiler like GCC.
  * libxtst-dev and libpng++-dev (`sudo apt-get install libxtst-dev libpng++-dev`).

Install node-gyp using npm:

```
npm install -g node-gyp
```

Then build:

```
node-gyp rebuild
```

See the [node-gyp readme](https://github.com/nodejs/node-gyp#installation) for more details.
