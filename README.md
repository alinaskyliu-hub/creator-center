# 创作者工作台

访问网站：https://alinaskyliu-hub.github.io/creator-center/

`website.zip` 包含完整静态网站源码（HTML、CSS、JavaScript、图片和测试），由 GitHub Actions 解压并发布至 GitHub Pages。

默认账号已绑定；`?linked=0` 为未绑定，`?linked=1` 为已绑定。仅为前端交互演示，不连接真实账号服务。

本地使用：解压后运行 `python3 -m http.server 8080`，打开首页。

测试：`node --test StudioDemo/assets/tests/*.test.cjs account_aurora/assets/tests/*.test.cjs`。
