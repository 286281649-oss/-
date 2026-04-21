# 宁波医疗中心李惠利医院影像专科联盟门户原型

这是一个可直接部署到 GitHub Pages 的静态原型项目。

## 本地预览

```bash
python3 -m http.server 4173
```

打开：

```text
http://localhost:4173/preview/effe45f0-9df3-4990-a770-c88193857859/7076723/
```

## GitHub Pages 部署

1. 新建一个 GitHub 仓库，例如 `lihuili-imaging-portal`。
2. 将本目录全部文件提交并推送到该仓库的 `main` 分支。
3. 在 GitHub 仓库中进入 `Settings` -> `Pages`。
4. `Build and deployment` 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`，保存。
6. 等待 GitHub Pages 部署完成。

部署后访问地址通常为：

```text
https://你的GitHub用户名.github.io/仓库名/preview/effe45f0-9df3-4990-a770-c88193857859/7076723/
```

根地址也会自动跳转到原型页面：

```text
https://你的GitHub用户名.github.io/仓库名/
```
