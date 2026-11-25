# 可替换图片目录

本目录是从博客项目中复制出来的可替换图片副本，原项目文件未移动、未修改。

目录结构沿用原项目路径，替换完成后可以按相同路径复制回项目。

## 当前使用中的图片

| 文件 | 博客位置 |
| --- | --- |
| `public/img/site_header_800.webp` | 小屏顶部横幅 |
| `public/img/site_header_1200.webp` | 中屏顶部横幅 |
| `public/img/site_header_1600.webp` | 桌面顶部横幅 |
| `public/img/site_header_1920.webp` | 大屏顶部横幅 |
| `public/img/avatar.webp` | 首页个人卡片、移动端抽屉、RSS 头像、默认分享图 |
| `public/img/cover/1.webp` 至 `public/img/cover/21.webp` | 文章卡片默认封面 |
| `public/img/cover/2.webp` | 首页“随笔”分类卡 |
| `public/img/cover/3.webp` | 首页“项目”分类卡 |
| `public/img/cover/4.webp` | 首页“技术”分类卡 |
| `public/img/cover/5.webp` | 首页“ACG”分类卡 |
| `public/favicon.ico` | 浏览器标签页图标 |

## 可选图片

| 文件 | 说明 |
| --- | --- |
| `src/assets/svg/logo.svg` | 顶部 Logo；当前 `showLogo: false`，不会显示 |
| `public/img/weekly_header.webp` | 精选系列页头图；当前未启用系列功能 |

## 当前未使用的图片

| 文件 | 说明 |
| --- | --- |
| `public/img/effects/holo.webp` | 当前代码未引用 |
| `public/img/effects/sparkles.gif` | 当前代码未引用 |

## 未包含的图片

《测试文章》正文中仍有一张外部测试图：

`https://pan.202548.xyz/file/web1/1795135939970_ScreenShot_2026-11-19_215142_002.png`

它不是项目内文件，因此没有复制到本目录。正式替换时可下载到 `public/img/`，再修改文章中的 Markdown 图片地址。

## 替换提醒

- `site_header_*.webp` 四张应一起替换，保持相同文件名。
- 建议文章封面使用 16:9、至少 800×450 的图片。
- 替换图片后执行 `pnpm koharu generate lqips` 重新生成图片占位色。
- 完整位置说明见项目文档 `docs/image-inventory.md`。
