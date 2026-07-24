# time-logger-site — 时间尺部署镜像

本仓库是 [`wowayou/time-logger`](https://github.com/wowayou/time-logger) 的**自动发布产物镜像**，
用于通过 GitHub Pages 承载 `time.eigentime.org`（`/` 产品主页，`/app/` PWA 应用）。

- **不要手工修改本仓库的任何文件**：内容由源码仓库的 `scripts/build_site.py`
  在版本 tag push 时经 GitHub Actions 自动生成并推送，人工改动会在下次发布时被覆盖。
- 源码、issue、决策记录、许可（AGPL-3.0-or-later）均在源码仓库。
- 本仓库不含任何密钥、用户数据或私有配置。

决策背景见源码仓库 `docs/decisions.md` D12。
