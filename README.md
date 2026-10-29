# AdGuard 开屏广告拦截补充规则

国产常用 App（快手/抖音/微博/B站/知乎/百度/淘宝/京东/拼多多/美团等）开屏广告素材 CDN 拦截规则。

## 使用方法

在 AdGuard（安卓）中：
1. 过滤器 → 自定义过滤器 → 添加自定义过滤器
2. URL 或路径填：
   `https://raw.githubusercontent.com/hc22180/adguard-splash-rules/master/splash_adguard.txt`
3. 下一步 → 完成

规则支持 AdGuard 定期自动更新。

## 说明
- 本规则拦截 App 开屏广告**素材下发的网络请求**，让开屏变黑屏/直接进首页
- **无法**自动点击「跳过」按钮（UI 层操作，需 GKD/李跳跳 工具配合）
- 命中漏网域名后可在 AdGuard 日志里追加规则
