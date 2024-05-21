# Bulk Terabox Downloader
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/HightechSec/Bulk-Terabox-DL)
![GitHub repo size](https://img.shields.io/github/repo-size/HightechSec/Bulk-Terabox-DL)
![GitHub last commit](https://img.shields.io/github/last-commit/HightechSec/Bulk-Terabox-DL)
![GitHub stars](https://img.shields.io/github/stars/HightechSec/Bulk-Terabox-DL)
![GitHub pull requests](https://img.shields.io/github/issues-pr/HightechSec/Bulk-Terabox-DL)
![GitHub forks](https://img.shields.io/github/forks/HightechSec/Bulk-Terabox-DL)
![GitHub issues](https://img.shields.io/github/issues/HightechSec/Bulk-Terabox-DL)
![GitHub watchers](https://img.shields.io/github/watchers/HightechSec/Bulk-Terabox-DL)
![License](https://img.shields.io/badge/License-GPL-blue.svg?style=flat)

## Preview
![1](https://raw.githubusercontent.com/HightechSec/Bulk-Terabox-DL/main/img/Preview.png)

## Install Depedency

- Clone this repo (`https://github.com/HightechSec/Bulk-Terabox-DL`)
- Install the Depedency first `sudo apt update && sudo apt install libc++-dev libunwind-dev -y`
- run `npm install`

## Change Environtment Variables in wrangler.toml 
- Fill the `JS_TOKEN, DP_LOGID, and COOKIES`
- Open a terabox file link then Open network tab
- Then search in the network tab for `"list?app_id"`, Open the Request and Copy all the Required Variables.
![1](https://raw.githubusercontent.com/HightechSec/Bulk-Terabox-DL/main/img/JS-Token.png)
![2](https://raw.githubusercontent.com/HightechSec/Bulk-Terabox-DL/main/img/Cookie.png) 

Everytime you get **"Failed get url download | Errno : 400310"** error, you must repeat the steps above to Change the Variables to a new `JS_TOKEN, DP_LOGID, COOKIES`

## Deploying Manually 
- run`npm run dev` to run it on your local machine
- or `npm run deploy` to deploy it to cloudflare pages
