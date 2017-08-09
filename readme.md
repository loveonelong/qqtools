# QQ工具（qqtools）

### 版本信息

> 这是我无聊写来玩的小工具，基于按键精灵的Q语言开发，有点类似于VBS。按键精灵会有一些广告，跟我本人没有关系，我也得不到任何收成。我比较懒，所以暂时没有空寻找更好的脚本平台，如果有更好的平台请联系我。
>
> 目前给附近的人点赞已经被官方限制为根据等级限制数量，最高等级每人每天才10个赞。这个工具现在就显得有点鸡肋了。

版本：v0.4.0

适应QQ版本：安卓QQ v7.1.5

适应机型：720\*1280，DPI320,海马玩模拟器

系统要求：需要root权限，必需联网使用（受按键精灵机制影响），KingRoot会误认为是病毒软件。

最后更新时间：2017.8.9

### 更新状态

新版更新说明：

- 适配手机QQ最近版本v7.1.5

未来更新：

- 如果腾讯的规定还是不变的话，可能考虑在回赞的时候判断对方是否是好友
- 也可能考虑给好友点赞（这个功能以前写过，但是因为一些bug删除掉了）

### 功能

- QQ赞附近的人
- QQ回赞赞我的人

### 开发信息

语言：Q语言

开发工具：按键精灵手机助手

### 资源目录

- 根目录

  - mqb ······ 按键精灵手机助手导出的打包后的脚本。未加密，可直接导入按键精灵手机助手查看。

  - codetext ······ 文本型源码。把所有的源码整理成文本，方便查看。

  - resource ······ 所用到的一些资源文件。
  - apk ······ 放置APK，包括历史版本。

因为Q语言类似于VB的语言，其ui语言类似于json，所以codetext目录下，把代码源文件修改为vb后缀，把ui源文件修改为json后缀。

### 使用帮助

1. 下载并安装最新版的apk安装包，目前为【qqtools.0.4.0.apk】。
2. 确认网络已经连接。打开工具时，会申请root权限，请一定授权，否则无法正常运行（坑爹的按键精灵的机智）。
3. 进入后在配置页面设置配置信息。
4. 配置好后，点击启动脚本，出现小蜜蜂图标。
5. 登陆QQ，切换到相应页面，点击小蜜蜂图标，点击启动。
6. 启动过程中可以点击小蜜蜂图标后，点击暂停，停止脚本运行。
7. 停止状态下，点击小蜜蜂图标后，点击设置图标，可再次进行配置，并重新运行脚本。
