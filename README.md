# Forest Archive / 山中遗迹

这是一个可直接部署到 GitHub Pages 的静态个人作品集网站。

## 文件结构

```txt
forest-archive-site/
├── index.html
├── README.md
├── .nojekyll
└── assets/
    ├── favicon.svg
    ├── css/
    │   └── style.css
    ├── js/
    │   └── main.js
    └── images/
        ├── forest-01.jpg
        ├── forest-02.jpg
        ├── forest-03.jpg
        ├── forest-04.jpg
        ├── forest-05.jpg
        ├── forest-06.jpg
        ├── forest-07.jpg
        ├── forest-08.jpg
        └── forest-09.jpg
```

## 本地预览

直接双击 `index.html` 即可打开。

也可以在文件夹中运行：

```bash
python -m http.server 8000
```

然后浏览器打开：

```txt
http://localhost:8000
```

## GitHub Pages 部署

1. 新建一个 GitHub 仓库，例如 `forest-archive`。
2. 把本文件夹里的所有内容上传到仓库根目录，确保 `index.html` 在根目录。
3. 进入仓库 `Settings` → `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，文件夹选择 `/root`。
6. 保存后等待部署完成。

最终地址通常是：

```txt
https://你的用户名.github.io/仓库名/
```

## 修改内容

- 改标题：编辑 `index.html` 中的 `<title>`、`h1`、每个章节的文字。
- 改图片：替换 `assets/images/` 里的图片，文件名保持不变即可。
- 改邮箱：搜索 `mailto:`，替换成自己的邮箱。
