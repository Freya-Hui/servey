# Chinese Luxury Branding Survey

这是问卷网站的 GitHub 仓库代码包。

## GitHub 仓库结构

请确保 GitHub 仓库根目录直接包含：

- `index.html`
- `vercel.json`
- `media/`

不要把整个 `GitHub仓库代码包_Vercel读取版` 文件夹作为子文件夹上传到仓库里。

## Vercel 设置

- Framework Preset: `Other`
- Build Command: 留空
- Output Directory: 留空
- Root Directory: 留空

Vercel 会直接从 GitHub 仓库读取 `index.html`，并把 `media` 里的视频作为本地静态资源展示。
