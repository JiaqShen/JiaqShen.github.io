# 沈嘉琪 · GitHub 个人主页

这是一个无需构建工具的静态个人主页，使用 GitHub Pages 发布。

## 发布前先替换

打开 `index.html`，搜索并修改：

1. `href="#"`：替换为你的 GitHub 个人主页地址。
2. `YOUR_EMAIL@example.com`：替换为你愿意公开的联系邮箱；公开网页不建议填写手机号。
3. 确认个人简介、研究状态、项目描述和实习时间与你最终公开的信息一致。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个公开仓库，仓库名必须是 `<你的 GitHub 用户名>.github.io`，例如 `yourname.github.io`。
2. 解压本文件，将 `index.html` 和 `README.md` 放在仓库根目录。
3. 提交并推送到 `main` 分支。
4. 打开仓库 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/ (root)`，保存。
5. 等待 GitHub Pages 构建完成，主页地址为 `https://<你的 GitHub 用户名>.github.io/`。

## 本地预览

直接用浏览器打开 `index.html` 即可预览。页面为响应式布局，手机和电脑均可浏览。
