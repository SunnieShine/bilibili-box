<p align="center">
  <!--图片显示比较慢，甚至打不开，所以这里暂时屏蔽掉。-->
  <!--
    <img width="400" src="./image/demo.png">
  -->
  <h3 align="center">BiliBili-Box</h3>
  <p align="center">把你 B 站的投稿视频搬迁显示到 Pinned Gist 上！</p>
</p>

---

## 👨‍💻 过程

### 准备工作

1. 创建新公开 GitHub Gist（[点击跳转](https://gist.github.com/)）；
1. 创建新的 access token ，确保勾选 `gist` 然后复制它. （[点击跳转](https://github.com/settings/tokens/new)）；
1. 在 B 站个人空间的链接中找到 UID。


### 步骤

1. 复刻（Fork）本仓库；
1. 编辑 [`.github/workflows/schedule.yml`](https://github.com/Sunnie-Shine/bilibili-box/blob/master/.github/workflows/main.yml#L27-L28) 文件的需要的环境变量：

   - **UID**： B 站用户 UID，例如我的地址 https://space.bilibili.com/23736703 里面的 `23736703`；
   - **GIST_ID**： 你的 gist 里的 ID。比如我的 gist 的地址是 `https://gist.github.com/Sunnie-Shine/e8ff9fc13066c6f8eed3ad28ae9e7638`，取出末尾的 `e8ff9fc13066c6f8eed3ad28ae9e7638` 就是 ID 了。

1. 前往仓库的 **Settings > Secrets**（注意是仓库的而不是用户自己的）；
1. 添加环境变量：**GH_TOKEN:** 刚刚复制好的 access token。

## 💖 版权声明

原项目受 [youtube-box](https://github.com/SinaKhalili/youtube-box) 启发，然后该项目又从别人家那里 fork 过来的（具体请参看 fork 的相关地址）。
<!-- 我个人并不会 TypeScript，但是我可以学。 -->

## ✨ 其他

还有更多类似本仓库的 pinned gist 项目，例如[这个](https://github.com/matchai/awesome-pinned-gists)。
