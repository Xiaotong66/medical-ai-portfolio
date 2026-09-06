# 医疗AI作品集网页

这是一个适合 GitHub Pages / Gitee Pages 的纯静态单页作品集，无需后端和外部依赖。

## 文件说明

- `index.html`：首页内容。
- `styles.css`：页面样式。
- `assets/profile.jpeg`：头像。
- `assets/pancreatic-cancer-demo.mp4`：胰腺癌CT动态预测系统演示视频。
- `assets/lung-adenocarcinoma-demo.mp4`：肺腺癌综合分析系统演示视频。
- `assets/health-agent-demo.mp4`：智能健康助手 Agent 系统演示视频，当前待补充。
- `assets/*.jpg`：证书与佐证材料截图。

## 替换视频

后续把 Agent 系统演示视频放进 `assets/` 文件夹，并使用下面文件名：

- `health-agent-demo.mp4`

如果你想用其他文件名，修改 `index.html` 里对应 `<source src="...">` 的路径即可。

## 视频大小建议

GitHub 单文件通常不要超过 100MB。为了微信里加载更稳，建议每个视频压缩到 20-40MB 左右，格式使用 H.264 编码的 `.mp4`。

## GitHub Pages 发布

1. 新建一个 GitHub 仓库，例如 `medical-ai-portfolio`。
2. 把本文件夹里的所有内容上传到仓库根目录。
3. 在仓库 `Settings` → `Pages` 中选择 `Deploy from a branch`。
4. Branch 选择 `main`，目录选择 `/root`，保存。
5. 等待 GitHub Pages 生成网址，通常是：
   `https://你的用户名.github.io/medical-ai-portfolio/`

## 微信扫码可访问建议

GitHub Pages 在微信内置浏览器通常可打开，但国内网络稳定性不如 Gitee Pages、腾讯云或阿里云。如果用于正式投递，可以优先测试：

- 微信扫码能否直接打开；
- 视频是否能在微信内播放；
- 页面加载速度是否稳定。

## 二维码制作

拿到最终网址后，用草料二维码、二维彩虹、腾讯文档二维码或浏览器二维码工具生成二维码。建议二维码下面写：

`作品集：医疗AI项目演示 / 论文成果 / 代码仓库`

简历中同时保留短链接，方便电子版点击和转发。
