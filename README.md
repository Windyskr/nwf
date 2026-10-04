# nwf（yyawf fork）

本项目是 [tiansh/yawf](https://github.com/tiansh/yawf) 的 fork，由 [Windyskr/nwf](https://github.com/Windyskr/nwf) 维护。在上游的微博过滤和界面清理功能基础上，增加首页自动跳转「最新微博」等改进。

## 安装与更新

先在浏览器中安装 Tampermonkey 或其他支持本脚本的用户脚本管理器，再点击下面的链接，按提示安装或更新：

[安装或更新本 fork 的脚本](https://raw.githubusercontent.com/Windyskr/nwf/yyawf/yyawf.user.js)

安装及更新地址均指向本仓库的 `yyawf` 分支。脚本的 `@updateURL` 和 `@downloadURL` 也使用该地址，后续更新由脚本管理器按自身设置检查。

已安装本 fork 旧版的用户，请通过上面的链接更新一次，以采用新的更新地址。从上游版本切换时，请先停用旧脚本，再安装本 fork。

## 功能

- 隐藏推广微博和首页广告位。
- 按关键词过滤微博、评论和热搜。
- 按用户过滤微博和评论。
- 清理导航、侧栏、微博内容和图标。
- 进入首页时自动跳转到当前登录账号的「最新微博」。

## 首页自动跳转

此功能默认开启，支持直接打开微博首页和站内返回首页。

在「药方设置 → 页面跳转」中可以关闭「进入首页时自动跳转到最新微博」。修改后刷新页面生效。

## 上游与许可

上游项目：[tiansh/yawf](https://github.com/tiansh/yawf)。原作者：田生（tiansh）。本 fork 保留原作者署名与 MPL-2.0 许可。
