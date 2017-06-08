# ShadowsocksX-NG-R8-Updater
A tool to get the latest version of ShadowsocksX-NG-R8.

## Update
### v1.2
Deal with both ".zip" and ".dmg".
Automatical Installation.

### v1.1
Adapted to ".zip" format.    

**Auto installation**.

## Usage

If you don not have Node and npm on your Mac:

`brew install node npm`

Install dependency:

`npm install cheerio request -g`

Enter the folder of the script, for example:

`cd ShadowsocksX-NG-R8-Updater`

Then you can use it by

`node updater.js`

Or make it executable by

`chmod +x updater.js `

And then run it by

`./updater.js`

And it will download the latest version of ShadowsocksX-NG-R8 to the same place of this script.

### Automatical Installation

When it tells you to close ShadowsocksX-NG, if you close it manually, ShadowsocksX-NG will open and start after installation; if you decided to ignore it, ShadowsocksX-NG will open after installation, but you will have to start it manually.


## Proxy

I asume you use ShadowsocksX-NG-R8 already and opened "HTTP Proxy", so the script use http://127.0.0.1:1087 as a default proxy server.

If you do not want to use a proxy, use `node updater.js -n`;

If you want to use another http proxy, use `node updater.js -y [server] [port]`. For example: `node updater.js -y 127.0.0.1 1087`. "http://" is added by default, no need to add manually.



## 2Do:

- [X] Install Automatically
- [X] Adapt to .zip and .dmg
- [ ] Costomize saving path
- [ ] Verify Sig
- [ ] Show download progress
- [ ] Port to Python



