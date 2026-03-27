# Docsify GitHub Pages 最小完整示例

## 目录结构

```text
index.html
.nojekyll
docs/
  README.md
  _sidebar.md
  guide/
    README.md
    install.md
    advanced/
      config.md
  api/
    README.md
    auth.md
```

## 本地预览

不要直接双击 `index.html`。

在项目根目录运行：

```bash
python3 -m http.server 8080
```

然后打开：

```text
http://localhost:8080/
```

## GitHub Pages 部署

1. 把所有文件上传到仓库根目录
2. 进入 `Settings -> Pages`
3. Source 选择你的分支（如 `main`）
4. Folder 选择 `/ (root)`
5. 保存，等待站点生效

`.nojekyll` 必须保留，否则 `_sidebar.md` 可能会被忽略。
