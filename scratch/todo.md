## Step by Step

1. [x] 用 `<img>` 显示出两张图片
2. [x] 用 `<canvas>` 显示出一张图片
3. [x] 要显示的图片要能放到 canvas 里面
4. [x] 要能根据图片的大小调整 canvas 的尺寸
5. [x] 用 `<canvas>` 显示出两张图片
6. [x] 用代码强行拼一个戴帽子的图案出来
7. [x] 提供一个图片的下载链接
8. [x] 在 canvas 中显示用户上传的图片
9. [x] 适配移动端的屏幕（基于 1）
10. [x] 控制 canvas 的样式和大小（基于 7）
11. [x] hammer.js demo usage
12. [x] use hammer rotate and rize hat (based on 6 & 11)
13. [x] 整理代码
14. [x] 能够上传头像并进行操作
15. [x] 显示两个可选的帽子
16. [x] 可以生成下载用的图片
17. [x] 加入更多的帽子
18. [x] 可以单击镜像帽子


- 发布
  - git page?
  - 更改默认图
  - 访问次数统计
- 功能优化
  - `pan` 的时候门限值太大
- 长按动作优化
  - 不触发系统的操作
- 微信分享优化
  - 图标、描述
- 测试
  - 小屏幕
  - 安卓机器

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

## 08

key: read file from input

ref: [javascript - Can I load a local file into an html canvas element? - Stack Overflow](http://stackoverflow.com/questions/13938686/can-i-load-a-local-file-into-an-html-canvas-element)

## 09

key: viewport

refs:

-[Using the viewport meta tag to control layout on mobile browsers - Mozilla | MDN](https://developer.mozilla.org/en-US/docs/Mozilla/Mobile/Viewport_meta_tag)
- [2048](https://gabrielecirulli.github.io/2048/)

## 11

Hammer.js 的 API 超级好用，Event 对象里面包含了差不多所有的需要的东西。

ref: [API - Hammer.js](http://hammerjs.github.io/api/)

## 18

key: mirror = scale + translate

ref: [Transformations - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Transformations)
