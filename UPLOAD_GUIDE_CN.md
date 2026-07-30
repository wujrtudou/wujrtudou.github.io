# GitHub Pages 上传说明

目标仓库：`wujrtudou/wujrtudou.github.io`

## 最简单的替换方式

1. 解压网站包。
2. 打开 GitHub 仓库 `wujrtudou/wujrtudou.github.io`。
3. 点击 **Add file → Upload files**。
4. 把解压后的全部内容上传到仓库根目录，包括完整的 `assets` 文件夹。
5. GitHub 提示同名文件时，使用新文件覆盖。
6. 在页面底部填写提交说明，例如：`Redesign academic website`。
7. 点击 **Commit changes**。
8. 打开 **Actions**，等待 Pages 部署出现绿色对勾。
9. 访问 `https://wujrtudou.github.io/`，必要时强制刷新浏览器。

## 必须保持的目录结构

```text
wujrtudou.github.io/
├── index.html
├── research.html
├── working-papers.html
├── publications.html
├── service.html
├── contact.html
├── 404.html
├── Jinran_Wu_CV.pdf
├── robots.txt
├── sitemap.xml
└── assets/
    ├── site.css
    ├── site.js
    └── favicon.svg
```

不要只上传 HTML 文件。缺少 `assets` 文件夹时，页面会失去样式和交互。

## Pages 设置

进入 **Settings → Pages**，确认：

- Source：`Deploy from a branch`
- Branch：`main`
- Folder：`/(root)`

网站正式地址：`https://wujrtudou.github.io/`


## Working Papers 更新

公开预印本集中放在 `working-papers.html`。新增论文时，复制一个 `<article class="working-paper working-paper-wide">...</article>` 区块并替换标题、作者、摘要和链接即可。
