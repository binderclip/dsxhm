## Step by Step

1. [x] 用 `<img>` 显示出两张图片
2. [x] 用 `<canvas>` 显示出一张图片
3. [x] 要显示的图片要能放到 canvas 里面
4. [x] 要能根据图片的大小调整 canvas 的尺寸
5. [x] 用 `<canvas>` 显示出两张图片
6. [x] 用代码强行拼一个戴帽子的图案出来
7. [x] 提供一个图片的下载链接
8. [ ] 在 canvas 中显示用户上传的图片

## 02

ref: [Basic usage of canvas - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

## 03

key: `scale`

ref: [Transformations - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Transformations)

## 04

key: `ctx.canvas.width`

## 05

key: 03 + 04

## 06

key: translate & rotate

ref: [Transformations - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Transformations)

## 07

生成用于下载的 dataURL，本质上 base64 的信息

refs:

- 跨域的问题解决
  - [javascript - 如何在 chrome extension 中使用 canvas 的 `toDataURL` 方法？ - SegmentFault](https://segmentfault.com/q/1010000002459456)
  - [image 跨域访问代码求解释 - SegmentFault](http://segmentfault.com/q/1010000000768672/a-1020000002436172)
  - [微信 webview 中利用 canvas 处理图片转成 base64 - Cinwell's Blog](http://cinwell.com/post/wechat-webview-canvas-image-base64)
- 生成下载链接
  - [<a> - HTML (HyperText Markup Language) | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#attr-download)
- PS. 微信分享的 JS API
  - [微信内置浏览器的JsAPI(WeixinJSBridge续)_Alien的笔记](http://www.baidufe.com/item/f07a3be0b23b4c9606bb.html)
