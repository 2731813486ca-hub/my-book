# GitHub Pages 发布说明

这个目录现在是一套可直接发布的静态网页：

- `index.html`：长文阅读页
- `styles.css`：页面样式
- `assets/lake-book.pdf`：当前网页对应的原稿 PDF
- `.nojekyll`：告诉 GitHub Pages 按普通静态站点发布

## 发布步骤

1. 新建一个 GitHub 仓库。
2. 把这个目录里的文件上传到仓库根目录。
3. 打开仓库的 `Settings`。
4. 进入 `Pages`。
5. 在 `Build and deployment` 里选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
6. 保存后等待几十秒到几分钟。
7. GitHub 会给你一个网址，打开就是网页阅读版。

## 以后怎么替换内容

如果只是换回原始 PDF：

1. 替换 `assets/lake-book.pdf`
2. 视情况改一下 `index.html` 里的标题和简介

如果还要继续保留“网页正文版”：

1. 替换 `assets/lake-book.pdf`
2. 同时更新 `index.html` 里的章节内容

这次已经把你指定的 `5.5` 整理稿替换成了当前网页使用的 PDF。
