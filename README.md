# 3V GitHub Pages Starter

这是一个可以直接发布到 GitHub Pages 的静态网站包。

## 最简单发布方式

1. 在 GitHub 新建一个仓库，例如 `3v-brand-site`
2. 把这个文件夹里的所有文件上传到仓库根目录
3. 打开仓库 `Settings`
4. 进入 `Pages`
5. Source 选择 `Deploy from a branch`
6. Branch 选择 `main`，Folder 选择 `/root`
7. 保存后等待 1-2 分钟

你的链接会类似：

```text
https://你的用户名.github.io/3v-brand-site/
```

## 后续替换网站

以后你做完自己的网站，只要把新网站导出的静态文件放到仓库根目录，保留 `index.html` 作为首页，就可以继续用同一个链接展示给客户。

## 文件说明

- `index.html`: 当前示例主页
- `.nojekyll`: 让 GitHub Pages 按普通静态网站发布
