# 副屏壁纸选择器

把 [Wallpaper Engine](https://store.steampowered.com/app/431960/) 的壁纸显示到 **TRCC（利民）USB 副屏** 上。
支持 Web / 视频 / 静态图片 / 3D 场景四类壁纸，免安装、免 Python，双击即用。

- **下载最新版**：[Releases](https://github.com/5544221/trcc-wallpaper-picker/releases/latest)
- **发布页（介绍 + 下载按钮）**：https://5544221.github.io/trcc-wallpaper-picker/

## 运行要求

| 依赖 | 说明 |
|---|---|
| Windows | 10 / 11（64 位） |
| TRCC 软件 | 已安装并能驱动副屏（目录含 `USBLCDNEW.exe`、`ffmpeg.exe`） |
| Wallpaper Engine | 已安装并订阅壁纸 |
| 副屏 | TRCC USB 副屏，已插好并被识别 |
| Python | 不需要，已打包进 exe |

## 安装

1. 从 Releases 下载 `TrccWallpaperPicker_v*.zip` 并解压到普通目录（`_internal/` 必须与 exe 同级）。
2. 双击 `启动壁纸选择器.bat`。
3. 首次运行自动探测 TRCC 路径、Steam 创意工坊目录、副屏分辨率；探测失败可手改 `config.json`。

## 仓库说明

- 本仓库只托管**发布页与安装包**，不含源码。
- 站点源码在 `site/`，由 GitHub Actions 自动部署到 Pages（`.github/workflows/pages.yml`）。
- 未做代码签名，首次运行可能触发 Windows SmartScreen 提示（更多信息 → 仍要运行）。
- 免费业余项目，不提供商业支持。
