# memos

一个轻量级、自托管的备忘录中心. ![demo](.\imgs\demo.png)

> 所谓`自托管`，是指该项目可以在用户自己的服务器上运行，而不依赖于第三方服务提供商。
>
> 这意味着我们可以完全控制自己的数据和应用程序，不需要担心第三方服务提供商的可靠性或安全性问题。
>
> 自托管通常需要一些技术知识和资源，但它可以提供更大的灵活性和自由度。
>
> 开源社区中，自托管是一个非常常见的概念，许多开源项目都支持自托管。



## 要点前瞻

- 开源&永久免费
- 在几秒内使用docker自托管
- 支持markdown
- 可定制和共享
- 用于自助服务的RESTful API

## docker部署

```bash
docker run -d --name memos -p 5230:5230 -v ~/.memos/:/var/opt/memos ghcr.io/usememos/memos:latest
```

>  `~/.memos/`目录将被用作本地机器上的数据目录， 而 `/var/opt/memos` 是数据卷在docker中的目录，不应该被修改。

详细安装目录参考这个链接: [other installation methods](https://usememos.com/docs/install).

## 客户端

---

- [Moe Memos](https://memos.moe/) - iOS和Android的第三方客户端
- [lmm214/memos-bber](https://github.com/lmm214/memos-bber) - Chrome 扩展
- [Rabithua/memos_wmp](https://github.com/Rabithua/memos_wmp) - WeChat 小程序
- [qazxcdswe123/telegramMemoBot](https://github.com/qazxcdswe123/telegramMemoBot) - 电报 bot
- [eallion/memos.top](https://github.com/eallion/memos.top) - 静态页面渲染 Memos API
- [eindex/logseq-memos-sync](https://github.com/EINDEX/logseq-memos-sync) - Logseq 插件
- [JakeLaoyu/memos-import-from-flomo](https://github.com/JakeLaoyu/memos-import-from-flomo) - 导入数据. 来自 flomo的支持, 微信阅读
- [Send to memos](https://sharecuts.cn/shortcut/12640) - iOS快捷方式
- [Memos Raycast Extension](https://www.raycast.com/JakeYu/memos) - Raycast扩展
- [Memos Desktop](https://github.com/xudaolong/memos-desktop) - MacOS and Windows三方客户端
