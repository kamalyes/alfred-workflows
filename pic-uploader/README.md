> Upload pictures with one click, support upload to imgur or vps


## requirement

brew install pngpaste


## compress support

500 times for free/per month

1. get api key https://tinypng.com/developers
2. setting tinypng_api_key
3. ensure visit https://tinypng.com is ok

## VPS uploader setting

configure the alfred environment variable

- user
- password
- destination
 
### connection test

`ssh -p 22 ${process.env.vps_user}@${process.env.vps_server}`


## Imgur Uploader setting
1. https://api.imgur.com/oauth2/addclient
   get clientId
2. configure the alfred environment variable

https://apidocs.imgur.com/



![](https://img.shields.io/badge/version-v2.7-green?style=for-the-badge)
[![](https://img.shields.io/badge/download-click-blue?style=for-the-badge)](https://github.com/kamalyes/alfred-workflows/raw/master/pic-uploader/Pic%20Uploader.alfredworkflow)
[![](https://img.shields.io/badge/plist-link-important?style=for-the-badge)](https://raw.githubusercontent.com/kamalyes/alfred-workflows/master/pic-uploader/src/info.plist)



<!-- more -->
> 系统截图，或者选中一个图片文件，直接一键即可上传到个人配置的图床服务，然后生成的Markdown图片地址已经存在系统剪切板中。


注意：截图生成的图片格式为`JPEG`

![](./2020-04-04-221152.gif)
