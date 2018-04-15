# quickapp-boilerplate

> 快应用骨架，for you ❤️

## Usage

```shell
# clone repo
$ git clone https://github.com/zce/quickapp-boilerplate.git my-project --depth 1
$ cd my-project

# install dependencies
$ yarn

# build rpk
$ yarn build

# start hmr server
$ yarn server
```

真机安装 [快应用调试器](https://statres.quickapp.cn/quickapp/quickapp/201803/file/quickapp_debugger.apk) 打开扫码即可体验。

## 可能遇到的问题

- 控制台不是等宽字体或者行高导致的二维码扫码不成功
  + 可以将监听的服务地址通过浏览器打开，扫描网页中的二维码即可
  + 也可以在`快应用调试器`中手动设置`服务器地址`为以上地址，然后点击`在线更新`
  + 或者手动将 `dist` 中的 `rpk` 文件拷贝到手机中，选择 `本地安装`
- 快应用调试器中显示无可用平台
  + 可以下载安装 [快应用平台正式版预览](https://statres.quickapp.cn/quickapp/quickapp/201803/file/quickapp_platform_preview_release.apk)
  + 如果你是这几个“山寨”厂商相对较新的手机，可以尝试更新手机系统到最新版本，然后更新系统内置应用

**当然你还有可能遇到各种问题，通常很多人把这种问题称之为“坑”，如果说这是“坑”的话，那么接下来你即将面临“坑王驾到”。**

理解吧！朋友们，比较都在抢时间，快应用的想法还是很不错的！短时间之内没有合适的开发团队支撑这个平台的开发和维护工作也很正常，我想你也面临过：你们公司的产品经理提出很不错的一个 Idea，结果因为你和你的小伙伴这样那样的原因不“给力”导致这个想法死在了起跑线上。

另外，喊话小米（我猜想这背后的开发主力军）：如果可以的话，呼吁开源快应用，不解释~
