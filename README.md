<p align="center">
  <img width="400" src="./image/demo.png">
  <h3 align="center">Bilibili-box</h3>
  <p align="center">把你 B 站的投稿视频搬迁显示到 Pinned Gist 上！</p>
</p>

---

> 📌✨ 还有更多类似本仓库的 pinned gist 项目，在这里: https://github.com/matchai/awesome-pinned-gists

## Setup

[English](./readme.md) | 中文


### Prep work

1. 创建新公开 GitHub Gist (https://gist.github.com/)
1. 创建新的 access token ，确保勾选 `gist` 然后复制它. (https://github.com/settings/tokens/new)
1. 在B站个人空间的链接中找到 UID，例如我的地址 https://space.bilibili.com/23736703 里面的 `23736703`。


### Project setup

1. 复刻本仓库
1. 编辑[环境变量](https://github.com/Sunnie-Shine/bilibili-box/blob/master/.github/workflows/main.yml#L27-L28)文件 `.github/workflows/schedule.yml`:

   - **UID:** B站用户标示.
   - **GIST_ID:** 你的 gist url 的 ID: `https://gist.github.com/matchai/`**`6d5f84419863089a167387da62dd7081`**.

1. 前往仓库的 **Settings > Secrets**
1. 添加以下环境变量:
   - **GH_TOKEN:** 刚刚复制好的 access token

### 版权

原项目受 [youtube-box](https://github.com/SinaKhalili/youtube-box) 启发，然后该项目又从别人家那里 fork 过来的（具体请参看 fork 的相关地址）。
<!-- 我个人并不会 TypeScript，但是我可以学 -->
