# Chinese Luxury Branding Survey

这是给 GitHub 仓库使用的 Vercel 稳定部署版。

## 仓库根目录必须有

- `index.html`
- `package.json`
- `vercel.json`
- `media/`

## 请在 GitHub 仓库里删除这些旧文件/文件夹

如果仓库里还存在下面这些旧内容，请删除：

- `vite.config.js`
- `vite.config.ts`
- `src/`
- `public/`
- `dist/`
- `node_modules/`
- 旧的 `.zip` 压缩包

## Vercel 设置

- Framework Preset: `Other`
- Build Command: `npm run build`
- Output Directory: `dist`
- Root Directory: 留空

如果 Vercel 显示 404，请先检查 GitHub 仓库首页第一层是否直接能看到 `index.html`。
