# GitHub Pages 部署说明

## 步骤

1. 在 GitHub 新建仓库（如 `watermark-tool`）
2. 把 `web/` 目录下的文件上传到仓库根目录
3. 进入仓库 Settings → Pages → Source 选 `main` 分支 → Save
4. 等约 1 分钟，访问 `https://你的用户名.github.io/watermark-tool/`

## 修改后端地址

打开 `index.html`，找到第一行 JS 配置：

```js
const API_BASE = 'https://your-domain.com' // ← 改成你的后端地址
```

## 本地预览

```bash
# 直接双击 index.html 打开即可
# 或用 VSCode Live Server 插件
```
