# 公开隐私与支持页

App Store Connect 的 Privacy Policy URL 和 Support URL 必须是**已上线的 HTTPS**。本目录是和 App 内同一份课文，不是第二份政策。

| 文件 | 用途 |
|---|---|
| `index.html` | 站点门口，链到政策和支持 |
| `privacy.html` | 简体隐私政策（Connect 主链接用这一页） |
| `privacy.zh-Hant.html` | 港繁（私隱） |
| `privacy.zh-TW.html` | 台繁（隱私） |
| `privacy.en.html` | English |
| `support.html` | 简体 App 支持（Connect 主链接用这一页） |
| `support.zh-Hant.html` | 港繁支援 |
| `support.zh-TW.html` | 台繁支援 |
| `support.en.html` | English support |

课文写的是现产品：7 天完整厨房试用，随后一次购买终身解锁（非消耗型 `com.cooktutor.kitchen.lifetime`）。不要再写「官方菜谱免费 / 我的厨房买断扩容私人菜」或订阅。未点名邮箱前不写联系地址。

GitHub Pages 由 `.github/workflows/legal-pages.yml` 发布。仓库 **Settings → Pages → Source = GitHub Actions**。合并到 `main` 后工作流部署，上线地址：

- 隐私：`https://florence2go.github.io/cooktutor-legal/privacy.html`
- 支持：`https://florence2go.github.io/cooktutor-legal/support.html`

`curl -I` 返回 200 再填 Connect。App 内设置和付费墙法律栏打开 `KitchenLegalPage` 同一组 HTTPS，按 `AppLanguage` 选当地页，不要再嵌一份课文。
