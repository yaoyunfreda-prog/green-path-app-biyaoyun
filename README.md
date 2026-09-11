# Green Path App（绿径）

**By Biyaoyun** · 植物探索、AR 扫描、一树一诗与园艺陪伴。

[打开绿径 App](https://yaoyunfreda-prog.github.io/green-path-app-biyaoyun/)

手机可直接在浏览器打开。iPhone 推荐 Safari；使用 AR 扫描时，请允许相机权限。

- 25 个可点击的作品集原型页面。
- 银杏、牵牛花、龟背竹、盆栽薄荷四种植物的图片识别与三维模型。
- 单台手机也可以选择植物图片，查看三维模型与诗句。
- 收藏和探索记录保存在当前设备；社区和兑换功能为作品集演示。

## AR 使用

在另一台设备打开[植物扫描卡](https://yaoyunfreda-prog.github.io/green-path-app-biyaoyun/targets.html)，用手机的 AR Scan 对准四张指定照片之一。识别目标为提供的照片，不是任意真实植物。

图片、模型和诗句说明见[素材来源](https://yaoyunfreda-prog.github.io/green-path-app-biyaoyun/credits.html)。

## 发布方式

本仓库保存已经构建好的静态网站。`site.zip.part01` 和 `site.zip.part02` 是同一个发布压缩包的两部分；GitHub Actions 合并、解压后部署到 GitHub Pages。这样部署时不依赖外部图片、三维模型 CDN 或应用服务器。

更新网站时，替换两部分发布文件并提交到 `main`；`.github/workflows/pages.yml` 会重新部署。静态文件可以同样部署到支持 HTTPS 的其他静态托管平台，并绑定自有域名。
